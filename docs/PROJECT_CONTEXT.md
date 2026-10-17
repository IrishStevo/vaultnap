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
- Apply this ordering after every future review refresh of Possible Games. The same automatic ordering now applies to Early Access when its review data is refreshed. Do not reorder any section not being refreshed.
- This ordering was introduced during the October 16 Possible Games review refresh; it did not validate classifications or descriptions.

## Early Access Steam review refresh — October 16, 2026

- Refreshed **all 21 Early Access games** directly from their Steam store page review summaries on October 16, 2026. Used **all-time English-language reviews** where Steam displayed them; otherwise used the all-time overall review summary. Excluded the recent 30-day review figures. Review totals are point-in-time figures and change over time.
- **Automatic sort required for every Steam review refresh:** descending positive-review Percent, then descending **exact review count** for ties. Applies independently to whichever review-bearing section(s) are refreshed (`Possible Games`, `Early Access`); do not re-sort untouched sections. Use actual review counts for ordering, not abbreviated displayed counts.
- Count display: exact integers below 1,000; otherwise `k` with one decimal, using half-up rounding (e.g. 1,250 → `1.3k`). This convention applies to both Possible Games and Early Access.
- **Only Early Access ratings, counts, and row order were changed in the games catalog**. Possible Games, Coming Soon, all game names/descriptions/links, and the Early Access Start/End fields remain unchanged. Game release statuses, three-player support, and suitability were not checked as part of this update.
- The AFTERBLAST store listing had last been crawled about two days before the October 16 check; all other 20 pages were crawled on the check date.
- Source for each game's score: the game-specific Steam store link in `games/README.md`. The exact counts below are retained for audit and future tie-breaking until next refreshed. `English` means Steam's English-language review total; `All` means Steam's all-time overall figure when no separate English figure was shown.

| Steam App ID | Game | Positive | Exact reviews | Scope |
| :--- | :--- | ---: | ---: | :--- |
| 2764460 | Sandustry | 97% | 3,342 | English |
| 3241660 | R.E.P.O. | 96% | 140,114 | English |
| 3124540 | Far Far West | 96% | 20,790 | English |
| 1962700 | Subnautica 2 | 93% | 72,649 | English |
| 1911610 | Windblown | 92% | 4,940 | English |
| 810040 | Swords 'n Magic and Stuff | 92% | 890 | All-time |
| 1857950 | Vein | 89% | 8,591 | English |
| 3041230 | Windrose | 88% | 28,846 | English |
| 1805320 | Romestead | 88% | 1,385 | English |
| 2786550 | Cure - A Hospital Simulator | 87% | 866 | All-time |
| 2661300 | Grounded 2 | 86% | 13,303 | English |
| 2412960 | Breathedge 2 | 86% | 1,729 | All-time |
| 2916430 | Fast Food Simulator | 85% | 4,479 | English |
| 1660080 | Aloft | 84% | 1,972 | English |
| 2679100 | Witchspire | 82% | 1,936 | All-time |
| 1548850 | Six Days in Fallujah | 81% | 9,582 | English |
| 768200 | Smalland: Survive the Wilds | 81% | 4,448 | English |
| 1805110 | Solarpunk | 81% | 1,973 | English |
| 1898300 | ASKA | 79% | 5,673 | English |
| 1338490 | Afterblast | 76% | 225 | All-time |
| 2479810 | Gray Zone Warfare | 74% | 47,067 | English |

## What has not been checked yet

- **Steam reviews:** Possible Games and Early Access review figures refreshed October 16, 2026; review data for Coming Soon is not tracked.
- **Release status and dates** may also be outdated; entries have not been reclassified based on current store information.
- **Three-player compatibility**, play modes, dedicated servers, and other gameplay suitability details have **not** been audited. Being listed does not guarantee a game supports three players in co-op.
- **Descriptions and non-Steam availability** have not been independently reviewed. Possible Games and Early Access are sorted by review metrics, which is not a recommendation ranking.
- The other worksheets in the original spreadsheet were intentionally **out of scope** for this first version.

## Future workflow

The owner will point future chats at `https://github.com/IrishStevo/vaultnap`. The assistant should read the current root README instructions, these notes, and the current games list. Agree on specific changes in chat; prepare a ZIP of only the files that should be added/replaced, accompanied by a suggested commit message. **Do not make GitHub changes through a connector or API.** The owner commits manually.

When the requested data review begins, work in user-directed steps rather than replacing the entire list or imposing new ranking/column schemes without approval. Record consequential decisions and completed checks here after the user decides to include them in a repo update.
