# Project context and handoff notes

This file holds **working context for future chats**, separate from the reader-facing [game list](../games/README.md). The root [README](../README.md#chatgpt-instructions) contains the authoritative collaboration rules; re-read it before repo work.

## Project status — October 16, 2026

- **Repository:** `IrishStevo/vaultnap` (default branch: `main`).
- **Purpose:** Find potential PC games for three friends to play together, primarily via Steam, on Windows 11 gaming PCs. Other PC storefronts are acceptable when needed.
- **Current candidate list:** `games/README.md`, converted from the user's `VaultNap Games List.xlsx` workbook. Only its **Possible Games**, **Early Access**, and **Coming Soon** worksheets were used.
- **Counts in this baseline:** 71 Possible Games, 21 Early Access, and 5 Coming Soon, for **97 rows** total.
- **Import approach:** Existing spreadsheet columns, entries, review percentages/counts, date values, and row order were carried across to GitHub-friendly Markdown tables, with clickable Steam links. Aside from the specific corrections below, the data was not refreshed or validated against current store information.

## Corrections already approved

1. **Big Walk:** The game appeared twice in Possible Games. Keep the first entry (96%, 22,000 reviews, “Open world puzzle adventure”) and discard the second duplicate (91%, 4,000 reviews).
2. **Romestead:** Fix the repeated URL so its link is `https://store.steampowered.com/app/1805320/Romestead/`.
3. **Outward:** Remove the spurious URL-encoded trailing backslash; use `https://store.steampowered.com/app/794260/Outward_Definitive_Edition/`.

## What has not been checked yet

- **Steam review percentages and counts** may be out of date; a review refresh is planned for a later task.
- **Release status and dates** may also be outdated; entries have not been reclassified based on current store information.
- **Three-player compatibility**, play modes, dedicated servers, and other gameplay suitability details have **not** been audited. Being listed does not guarantee a game supports three players in co-op.
- **Descriptions, ordering, and non-Steam availability** have not been independently reviewed.
- The other worksheets in the original spreadsheet were intentionally **out of scope** for this first version.

## Future workflow

The owner will point future chats at `https://github.com/IrishStevo/vaultnap`. The assistant should read the current root README instructions, these notes, and the current games list. Agree on specific changes in chat; prepare a ZIP of only the files that should be added/replaced, accompanied by a suggested commit message. **Do not make GitHub changes through a connector or API.** The owner commits manually.

When the requested data review begins, work in user-directed steps rather than replacing the entire list or imposing new ranking/column schemes without approval. Record consequential decisions and completed checks here after the user decides to include them in a repo update.
