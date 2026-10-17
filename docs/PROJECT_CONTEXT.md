# Project context and handoff notes

This file holds **working context for future chats**, separate from the reader-facing [game list](../games/README.md). The root [README](../README.md#chatgpt-instructions) contains the authoritative collaboration rules; re-read it before repo work.

## Project status — October 16, 2026

- **Repository:** `IrishStevo/vaultnap` (default branch: `main`).
- **Purpose:** Find potential PC games for three friends to play together, primarily via Steam, on Windows 11 gaming PCs. Other PC storefronts are acceptable when needed.
- **Current candidate list:** `games/README.md`, converted from the user's `VaultNap Games List.xlsx` workbook. Only its **Possible Games**, **Early Access**, and **Coming Soon** worksheets were used.
- **Counts in this baseline:** 71 Possible Games, 21 Early Access, and 5 Coming Soon, for **97 rows** total.
- **Import approach:** Existing spreadsheet columns, entries, review percentages/counts, date values, and row order were carried across to GitHub-friendly Markdown tables, with clickable Steam links. Apart from specifically approved changes, the other imported data has not been refreshed or validated.

## Corrections already approved

1. **Big Walk:** The game appeared twice in Possible Games. Keep the first entry (96%, 22,000 reviews, “Open world puzzle adventure”) and discard the second duplicate (91%, 4,000 reviews).
2. **Romestead:** Fix the repeated URL so its link is `https://store.steampowered.com/app/1805320/Romestead/`.
3. **Outward:** Remove the spurious URL-encoded trailing backslash; use `https://store.steampowered.com/app/794260/Outward_Definitive_Edition/`.

## Steam review refresh — October 16, 2026

- Updated the **Percent** and **Count** fields for all **71 Possible Games** using Steam's **all-time** review summaries (English-language where Steam displayed a separate English breakdown), not the recent 30-day figures. **Outbound** and **Kiln** used the all-time summary shown on their store pages without a separate English split. Some age-gated entries were checked against recently indexed official Steam store listings instead of directly accessible store pages.
- Review counts are shown as the **actual integer below 1,000** or as **thousands to one decimal place** (`k`) with conventional half-up rounding at or above 1,000 (for example, 1,278 → `1.3k`; 998 → `998`). The exact source counts were consulted; the README intentionally uses rounded display figures.
- Kept game titles, links, descriptions, original row order, and section assignments intact. **Early Access** and **Coming Soon** remain unchanged, including their historical review figures.
- Review totals change over time; these are a snapshot, not continuously refreshed values.

## Possible Games ordering — October 16, 2026

- **Approved ordering:** Sort the 71 **Possible Games** by **Percent descending**. If games share the same percentage, sort by **actual Steam review count descending**. Use the exact source count from the review refresh rather than the displayed `k` number (two different totals may round to the same displayed figure).
- **Review count formatting:** Display the exact integer if it is below 1,000; at 1,000 or above, use `k` with one digit after the decimal and conventional half-up rounding. Do not use the rounded display count for sorting.
- Apply this ordering again after each future refresh of Possible Games review numbers. Keep unrelated catalog content, including **Early Access** and **Coming Soon**, unchanged unless requested.
- This change applies the review data from the October 16 refresh; it does not fetch newer figures or validate classifications or descriptions.

## What has not been checked yet

- **Early Access Steam review percentages and counts** have not been refreshed; Possible Games reviews were refreshed October 16, 2026.
- **Release status and dates** may also be outdated; entries have not been reclassified based on current store information.
- **Three-player compatibility**, play modes, dedicated servers, and other gameplay suitability details have **not** been audited. Being listed does not guarantee a game supports three players in co-op.
- **Descriptions and non-Steam availability** have not been independently reviewed. Possible Games is sorted by review metrics, which is not a recommendation ranking.
- The other worksheets in the original spreadsheet were intentionally **out of scope** for this first version.

## Future workflow

The owner will point future chats at `https://github.com/IrishStevo/vaultnap`. The assistant should read the current root README instructions, these notes, and the current games list. Agree on specific changes in chat; prepare a ZIP of only the files that should be added/replaced, accompanied by a suggested commit message. **Do not make GitHub changes through a connector or API.** The owner commits manually.

When the requested data review begins, work in user-directed steps rather than replacing the entire list or imposing new ranking/column schemes without approval. Record consequential decisions and completed checks here after the user decides to include them in a repo update.
