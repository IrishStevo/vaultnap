# Project context and handoff notes

This file holds **working context for future chats**, separate from the reader-facing [game list](../games/README.md). The root [README](../README.md#chatgpt-instructions) contains the authoritative collaboration rules; re-read it before repo work.

## Current state — October 26, 2026

**Handoff update (October 26, 2026):** The root README provides a copyable new-chat prompt and a **Pending updates** queue. Previously queued items (over the hill, Trash Day, Palworld Played transfer, and Co-Optimus) have already been applied and remain included. The queue is empty. Future individually approved games may be queued without an individual ZIP; the next requested repository update or `Update games` run can apply them without conducting new discovery.

**This section is the current handoff after the October 26 game-discovery additions; the full existing-game review refresh was also October 26.** The dated entries below it are retained as a chronological history; older statements about counts, row order, unfinished work, or changed-files-only ZIPs are **historical and superseded** by the root [ChatGPT Instructions](../README.md#chatgpt-instructions), [Update games runbook](UPDATE_GAMES.md), the [Find new games runbook](FIND_NEW_GAMES.md), and the current [game catalog](../games/README.md).

| Catalog section | Active rows | Sorting |
| :--- | ---: | :--- |
| Possible Games | **91** | Review Percent descending, then exact review count descending |
| Early Access | **35** | Review Percent descending, then exact review count descending |
| Coming Soon | **27** | Soonest first; `n/a` last, alphabetically |
| Played | **24** | Most recent `When` first; alphabetical title ties |

- **153 active candidates** across the first three sections; **177 rows** including Played history. Sections are not guaranteed to be mutually exclusive with Played, which is historical.
- **Reviews:** The [review snapshot](REVIEW_SNAPSHOT.md) now covers **all 126 active review-bearing entries**. 110 preexisting records retain their own check dates, while the 16 additions have a dated October 26, 2026 indexed-Steam observation; most preexisting figures were also rechecked October 26;  Borderlands 3, Red Dead Online, and The Division 2 retain earlier dated figures due to age-gated/stale official listings. Seven exclusions and the Palworld Played transfer are preserved as separate historical records.
- **Release timelines:** All 28 Early Access and 21 pre-refresh Coming Soon entries were checked against current Steam status on October 26, 2026; Call of Duty: Modern Warfare 4 reached 1.0 and moved to Possible Games. Existing EA Start/Est. End and other Coming Soon When fields remain where no newer reliable official target was established.
- **Exclusions:** Eight explicitly removed candidate games and sixteen declined discovery suggestions are listed in their historical sections below. Don't reintroduce or re-suggest them without explicit owner approval.
- **Compatibility:** Native three-person co-op is an important group requirement; a comprehensive mode-by-mode check of every active candidate remains outstanding. New games require an appropriate three-person cooperative mode without unsupported mods. Recent Early Access and Coming Soon additions have co-op listings, but modes, progression, and polish can vary. Three tentative Coming Soon games (BLACKFROST, Chrono Odyssey, The CUBE) have **unresolved group-size or progression details**; do not claim a confirmed three-person implementation.
- **Commands:** [`Update games`](UPDATE_GAMES.md) refreshes current games and applies any future explicitly approved items in the root README Pending updates queue; [`Find new games`](FIND_NEW_GAMES.md) researches candidates for approval. Co-Optimus is an approved source for Possible Games discovery. No pending items remain after this update.
- **Packaging:** Every proposed repository update is a **ZIP including all Markdown documentation**, even unchanged files, plus any changed non-documentation files and a suggested commit message. The owner merges it into the existing repository and commits manually. GitHub access by the assistant is read-only.

## Owner-approved discovery additions — October 26, 2026

- **Decision:** Owner approved 23 new game entries after `Find new games` research: **9 Possible Games, 7 Early Access and 7 Coming Soon**. Owner declined **Elden Ring Nightreign** and **John Carpenter's Toxic Commando**; these are intentionally excluded from future automatic suggestions, joining the earlier 14 declined titles (now **16 declined discoveries**, plus the eight previously removed catalog games). No game in `Played` was changed and no existing game's reviews or release timing were independently refreshed during this discovery-additions update.
- **New totals:** **91 Possible Games, 35 Early Access, 27 Coming Soon, 24 Played** = **153 active candidates** and **177 combined rows**. Snapshot: **126 active review-bearing entries**, **seven separate owner-removed historical review records** and the separate Palworld moved-to-Played record.
- **Review provenance:** New Possible/Early Access records below reflect all-time review observations from **indexed official Steam store pages checked October 26, 2026**, English-language summary when individually exposed, otherwise all-time Overall. An index can lag the live Steam store and some direct pages were inaccessible; retain exact source counts and actual check date rather than misrepresenting these as live review reads. **Only these sixteen newly approved games** received new snapshot records. The previous 110 retained their historical exact counts, percentages, scope, access and `Checked` values; their existing ranking among themselves may shift only as necessary to merge the new titles by exact-count sorting. No recent-only reviews were substituted.

| New game | Section | Steam app ID | All-time Percent | Exact reviews | Scope | Official store |
| :--- | :--- | ---: | ---: | ---: | :--- | :--- |
| Rotwood | Possible Games | 2015270 | 90% | 2,234 | English | [Steam](https://store.steampowered.com/app/2015270/) |
| Unrailed 2: Back on Track | Possible Games | 2211170 | 88% | 1,829 | Overall | [Steam](https://store.steampowered.com/app/2211170/) |
| Wildmender | Possible Games | 1599330 | 85% | 1,806 | Overall | [Steam](https://store.steampowered.com/app/1599330/) |
| Escape Simulator 2 | Possible Games | 2879840 | 92% | 1,969 | English | [Steam](https://store.steampowered.com/app/2879840/) |
| Scrap Mechanic | Possible Games | 387990 | 90% | 48,187 | English | [Steam](https://store.steampowered.com/app/387990/) |
| PowerWash Simulator 2 | Possible Games | 2968420 | 92% | 7,511 | English | [Steam](https://store.steampowered.com/app/2968420/) |
| Luma Island | Possible Games | 2408820 | 90% | 3,769 | English | [Steam](https://store.steampowered.com/app/2408820/) |
| Aragami 2 | Possible Games | 1158370 | 76% | 1,564 | English | [Steam](https://store.steampowered.com/app/1158370/) |
| Voidtrain | Possible Games | 1159690 | 71% | 4,424 | English | [Steam](https://store.steampowered.com/app/1159690/) |
| StarRupture | Early Access | 1631270 | 81% | 6,980 | English | [Steam](https://store.steampowered.com/app/1631270/) |
| Delverium | Early Access | 2710040 | 86% | 178 | Overall | [Steam](https://store.steampowered.com/app/2710040/) |
| Roadside Research | Early Access | 3643170 | 87% | 2,288 | English | [Steam](https://store.steampowered.com/app/3643170/) |
| Permafrost | Early Access | 2254990 | 71% | 1,819 | Overall | [Steam](https://store.steampowered.com/app/2254990/) |
| MIMESIS | Early Access | 2827200 | 78% | 2,111 | English | [Steam](https://store.steampowered.com/app/2827200/) |
| Slay the Spire 2 | Early Access | 2868840 | 91% | 71,460 | English | [Steam](https://store.steampowered.com/app/2868840/) |
| Wild Woods | Early Access | 1975580 | 78% | 1,766 | Overall | [Steam](https://store.steampowered.com/app/1975580/) |

- **Early Access launches/targets:** StarRupture (Jan 6, 2026; 2027 developer 1.0 target); Delverium (Sep 21, 2026; 2028 is a broad derived end period based on an approximately two-year Early Access plan, not a committed full-release date); Roadside Research (Feb 12, 2026; no usable current 1.0 target); Permafrost (Oct 9, 2026; no usable current 1.0 target); MIMESIS (Oct 27, 2025; no usable current 1.0 target); Slay the Spire 2 (Mar 5, 2026; 2028 a derived upper-year estimate from the developer's approximate 1–2 year plan); Wild Woods (Dec 9, 2024; no usable current 1.0 target). Steam-specific [source listings](https://store.steampowered.com/) are linked by app ID in the review table above. Derived 1.0 forecasts can change and are not verified release commitments.
- **Coming Soon first-public-release plan (current check October 26, 2026):** ATMOSFAR — `EA Oct 29, 2026` ([Steam](https://store.steampowered.com/app/1798230/)); Totally Safe Moon Project — `Oct 30, 2026` ([Steam](https://store.steampowered.com/app/4339680/)); DUSTBLOOM — `EA Nov 10, 2026` ([Steam](https://store.steampowered.com/app/5157580/)); Dumpster Gang — `Dec 3, 2026` ([Steam](https://store.steampowered.com/app/2870790/)); Frostrail — `EA Q4 2026` ([Steam](https://store.steampowered.com/app/3517740/)); Voidwood — `2027` ([Steam](https://store.steampowered.com/app/3694420/)); 4:LOOP — `n/a` ([Steam](https://store.steampowered.com/app/3355360/)). Calendar dates are announced *targets*, not confirmed future releases; `EA` denotes an announced initial public Steam Early Access launch. Periods sort by their last possible day. The `n/a` entry has no verified release target.
- **Compatibility caveats:** Most additions offer native three-person-or-larger co-op without mods, but individual modes, host saves, progress sharing and forthcoming features are not all guaranteed. MIMESIS recommends a four-person group and requires a microphone. 4:LOOP advertises a four-person squad structure; future PC account and mode restrictions should be rechecked near launch. Permafrost was newly available in EA and may benefit from polish. Three-player support does not mean that every single-player campaign mode is shared.
- **Scope and packaging:** `games/README.md` has only the new approved entries integrated into the established separate sorts, and the `Played` table remains unchanged. `docs/REVIEW_SNAPSHOT.md` reconciles all active app IDs to exact source counts and preserves historical-only records. This manual-commit proposal includes every Markdown document, unchanged or changed; no GitHub or service writes were made.

## Update games — October 26, 2026 (latest full refresh)

- **Scope:** Maintenance only. Re-fetched the latest GitHub documentation once, reused local files after matching Git blob hashes, and audited the **existing** 81 Possible, 28 Early Access, and 21 Coming Soon games. No unapproved discoveries were added. All 24 Played entries (including Palworld — Steve, Oct 2026) were preserved unchanged. There were no outstanding approved pending additions.
- **Verified release transfer:** [Call of Duty: Modern Warfare 4](https://store.steampowered.com/app/4435490/) has released in full (Steam local release **October 22, 2026**, with the publisher previously announcing worldwide October 23). Move it from Coming Soon into Possible Games, retaining its exact existing Steam link and description. Its observed **79% of 4,567 English-language all-time reviews** enter the active review snapshot. It is distinct from the existing generic Call of Duty Steam app entry.
- **New counts:** **82 Possible Games**, **28 Early Access**, **20 Coming Soon**, **24 Played**; **130 active candidates**, **154 catalog rows** in total. `docs/REVIEW_SNAPSHOT.md` holds **110 active reviews** plus the preexisting historical exclusions/transfer. No other candidate moved sections.
- **Reviews:** Rechecked all accessible Steam all-time English summaries where offered, otherwise all-time Overall, and substituted recently indexed *official Steam* reviews for some age-gated listings. Re-sort Possible and Early Access by **Percent descending, exact review count descending** and reconcile all exact counts/dates in snapshot. Each row is individually dated; review data is an observation rather than a live feed. **Unrefreshed exceptions:** Borderlands 3 (`397540`), Red Dead Online (`1404210`), The Division 2 (`2221490`); newer figures were not verifiable from a sufficiently current official Steam summary, so retain their previous precise counts, review percentages, and their historical `Checked` dates. Indexed listings may lag the October 26 check.
- **Notable rating changes** compared with saved figures: RuneScape: Dragonwilds **82% → 81%**; Once Human **80% → 81%**; Medieval Dynasty **89% → 88%**; Grounded 2 **86% → 87%**; Fast Food Simulator **85% → 84%**; Gears of War: E-Day **71% → 70%**. Steam data sources: individual game store pages `https://store.steampowered.com/app/<Steam App ID>/` (some via indexed listings). Scope is English unless marked Overall in snapshot.
- **Early Access status and timelines:** All 28 remain marked Early Access on their current Steam pages, including Lightyear Frontier, whose Steam 1.0 target is **November 4, 2026**, a future date as of the audit. The previously verified launch `Start` and developer-based `Est. End` columns remain in place; no more reliable superseding target was found in this pass. Some forecasts are developer estimates or computed upper bounds, not promised release dates. Recheck expired 2026 targets next run.
- **Coming Soon dates:** Checked the status of every one of the prior 21 listings. Aside from Modern Warfare 4 releasing, the remaining 20 still show Coming Soon/TBA and no verified new date superseded their existing developer-backed `When` fields. Preserve `EA` marker for confirmed Early Access first launches, and keep date-scoped earliest-first sorting, unknown `n/a` titles last alphabetical. Chrono Odyssey was age-gated; its accessible indexed Steam page still shows TBA. Source: individual official Steam listings, including https://store.steampowered.com/app/2873440/.
- **Workflow efficiency:** Added `AGENTS.md#efficient-repository-updates` with instructions to fetch docs once, prefer matching-hash local copies, limit edits, validate proportionally, and include unchanged Markdown files directly in the final ZIP. The root README links to those rules. No GitHub writes or service modifications were performed.

## Historical decisions and audits (chronological)

## Project status — October 16, 2026 (historical import baseline)

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

## Early Access start/end audit — October 16, 2026 (historical, before reclassification)

- **Coverage:** Checked all 21 Early Access rows against their Steam product listings and developers' Early Access statements, plus official announcements where relevant. All original **Start** dates were consistent with Steam's Early Access launch dates **except Smalland and Solarpunk**. This audit changes *only* the `Start` and `End` columns in `games/README.md`, leaving review values, row order, descriptions and other sections intact.
- **Conventions:** `Start` = launch *into Early Access* on Steam; `End` = actual full-release date (for completed Early Access) or current developer-stated full-release timing. `(planned)` = explicit developer calendar target (not a guarantee); `(est.)` = calendar window **derived from the developer's stated Early Access duration** and the verified start date (not a promised release date). Use `n/a` where no meaningful current target exists. Never interpret a minimum duration, an expired estimate or a product's launch directly into 1.0 as a confirmed Early Access end date.
- **Important classification issues (left for owner's separate approval):** **Smalland: Survive the Wilds** actually started Early Access **Mar 29, 2023**, then launched 1.0 **Feb 15, 2024**. Both dates are now recorded; it no longer belongs in Early Access. **Solarpunk** launched directly into **1.0 on Jun 8, 2026** without Steam Early Access (confirmed by the publisher's press kit and developer release announcement). The original `Start` was actually its full-release date; `Start` and `End` are both now `n/a` because neither Early Access date applies. Both rows stay in their existing section until the owner requests reclassification. [Smalland Steam](https://store.steampowered.com/app/768200/Smalland_Survive_the_Wilds/), [Solarpunk publisher press kit](https://www.metaroot.ch/press-kit/solarpunk), [Solarpunk developer release announcement](https://www.solarpunk.tools/news/solarpunk-finally-has-a-release-date).
- **Outdated developer targets:** R.E.P.O.'s original ~18-month target from Feb 2025 would put 1.0 around Aug 2026, but the game remains in Early Access; no newer reliable date was found. Fast Food Simulator's original ~6–12 months from Dec 2024 lapsed in 2025; ASKA's 2025 plan lapsed; Six Days in Fallujah's EA FAQ still says late 2025, but its **newer on-page roadmap targets late 2026** (used in the catalog). Older or ambiguous estimates were not substituted as current release targets.
- **Other non-committal statements:** Aloft and Witchspire give a **minimum** stay (at least one year), not a release date; Swords 'n Magic and Stuff uses an unanchored "at least one more year"; Grounded 2 and AFTERBLAST provide no target; Gray Zone Warfare says "several years." Their `End` remains `n/a` unless an actionable current developer date/window is found.
- **Scope boundary:** Steam review percentages/counts **were not refreshed** in this timeline audit. The established rating-based order in Early Access and Possible Games was retained. A separate compatibility audit should note that Steam currently lists Sandustry as single-player only; no multiplayer verification was requested or performed comprehensively.

| Game | End recorded | Developer evidence and interpretation |
| :--- | :--- | :--- |
| [Sandustry](https://store.steampowered.com/app/2764460/Sandustry/) | Aug 2027 (est.) | Developer plans ~1 year of Early Access beginning Aug 13, 2026. |
| [R.E.P.O.](https://store.steampowered.com/app/3241660/REPO/) | n/a | Around 18 months estimated at original launch; resulting Aug 2026 target has elapsed while game is still EA. |
| [Far Far West](https://store.steampowered.com/app/3124540/Far_Far_West/) | Apr 2027 (est.) | Developer plans 12 months from Apr 28, 2026. |
| [Subnautica 2](https://store.steampowered.com/app/1962700/Subnautica_2/) | 2028–2029 (est.) | Developer expects approximately 2–3 years of EA from May 14, 2026. |
| [Windblown](https://store.steampowered.com/app/1911610/Windblown/) | 2026 (planned) | Motion Twin explicitly targets an exit sometime in 2026. |
| [Swords 'n Magic and Stuff](https://store.steampowered.com/app/810040/Swords_n_Magic_and_Stuff/) | n/a | No reliably dated current release window; 'at least 1 more year' is not a calendar target. |
| [VEIN](https://store.steampowered.com/app/1857950/VEIN/) | 2030 (est.) | Developer estimates roughly five years to feature-completion **if working full time**, from Oct 2025; highly conditional. |
| [Windrose](https://store.steampowered.com/app/3041230/Windrose/) | Late 2027–Late 2028 (est.) | Developer anticipates ~1.5–2.5 years from Apr 14, 2026. |
| [Romestead](https://store.steampowered.com/app/1805320/Romestead/) | 2027–2028 (est.) | Developer anticipates ~1–2 years from May 25, 2026. |
| [CURE - A Hospital Simulator](https://store.steampowered.com/app/2786550/CURE__A_Hospital_Simulator/) | Late 2026–Late 2027 (est.) | Developer currently states ~12–24 months from Nov 20, 2025. |
| [Grounded 2](https://store.steampowered.com/app/2661300/Grounded_2/) | n/a | Obsidian explicitly declines a hard timeline. |
| [Breathedge 2](https://store.steampowered.com/app/2412960/Breathedge_2/) | Late 2027–Spring 2028 (est.) | Developer expects ~16–20 months from Aug 31, 2026. |
| [Fast Food Simulator](https://store.steampowered.com/app/2916430/Fast_Food_Simulator/) | n/a | Original 6–12 month estimate from Dec 2024 has passed, with no verified replacement. |
| [Aloft](https://store.steampowered.com/app/1660080/Aloft/) | n/a | "At least a year" from Jan 2025 is a minimum, now elapsed. |
| [Witchspire](https://store.steampowered.com/app/2679100/Witchspire/) | n/a | "At least a year" from Jun 2026 gives only a minimum, not a forecast date. |
| [Six Days in Fallujah](https://store.steampowered.com/app/1548850/Six_Days_in_Fallujah/) | Late 2026 (planned) | Updated developer roadmap on the same Steam page supersedes an older late-2025 FAQ. |
| [Smalland: Survive the Wilds](https://store.steampowered.com/app/768200/Smalland_Survive_the_Wilds/) | Feb 15, 2024 | Actual 1.0 exit; **Start corrected to Mar 29, 2023**. |
| [Solarpunk](https://www.metaroot.ch/press-kit/solarpunk) | n/a | No Early Access phase; launched directly as 1.0 on Jun 8, 2026. |
| [ASKA](https://store.steampowered.com/app/1898300/ASKA/) | n/a | 2025 full-release plan has lapsed; game still in EA in Oct 2026. |
| [AFTERBLAST](https://store.steampowered.com/app/1338490/AFTERBLAST/) | n/a | No time-bound developer target. |
| [Gray Zone Warfare](https://store.steampowered.com/app/2479810/Gray_Zone_Warfare/) | n/a | Developer gives only "several years," with no narrower current period. |

## Early Access classification and compact End dates — October 16, 2026

- Rechecked all 21 titles in the then-current Early Access section against their current Steam product listings. **19** retain Steam's Early Access status; **2** do not and have been transferred to Possible Games:
  - **Smalland: Survive the Wilds** — Early Access began Mar 29, 2023 and ended with full 1.0 release **Feb 15, 2024**. Steam: https://store.steampowered.com/app/768200/.
  - **Solarpunk** — launched directly as 1.0 **Jun 8, 2026**, without a Steam Early Access phase. Steam: https://store.steampowered.com/app/1805110/; publisher press kit: https://www.metaroot.ch/press-kit/solarpunk.
- **Current section totals:** 73 Possible Games, 19 Early Access, 5 Coming Soon (**97 distinct game rows** overall). Moved games retain their October 16 review scores and display counts (Smalland: 81%, 4.4k; Solarpunk: 81%, 2.0k). Inserted below RuneScape: Dragonwilds in Possible Games, correctly positioned under the existing rating/count ordering; no Steam review values were re-fetched.
- **Compact `End` display rule:** omit `(est.)` and `(planned)` from the catalog. When a developer quoted a range, display **only the final/high end** of that range (for example 2028–2029 becomes `2029`, Late 2027–Late 2028 becomes `Late 2028`). The catalog's brevity **does not make estimates guaranteed release dates**. `Start` remains the historic EA entry date; `n/a` still means no usable current end date. Keep full date provenance in this document.
- The abbreviated End values, with their underlying meanings, are:

| Game | Catalog End | Nature of underlying timing |
| :--- | :--- | :--- |
| Sandustry | Aug 2027 | Derived from ~1 year EA duration after Aug 13, 2026 |
| Far Far West | Apr 2027 | Derived from ~12 months EA duration after Apr 28, 2026 |
| Subnautica 2 | 2029 | Upper end of estimated 2028–2029 based on ~2–3 years EA |
| Windblown | 2026 | Explicit developer 1.0 year target |
| VEIN | 2030 | Conditional ~5-year feature-completion estimate assuming full-time work; not a firm 1.0 promise |
| Windrose | Late 2028 | Upper end of derived Late 2027–Late 2028 window (~1.5–2.5 years EA) |
| Romestead | 2028 | Upper end of derived 2027–2028 window (~1–2 years EA) |
| CURE - A Hospital Simulator | Late 2027 | Upper end of derived Late 2026–Late 2027 window (~12–24 months EA) |
| Breathedge 2 | Spring 2028 | Upper end of derived Late 2027–Spring 2028 window (~16–20 months EA) |
| Six Days in Fallujah | Late 2026 | Explicit updated developer roadmap target |

- All other 9 remaining Early Access rows keep `End = n/a`. The game descriptions, Steam links, percentages, review counts, start dates, and the relative order of remaining Early Access entries are unchanged. Coming Soon is untouched.
- **Standing workflow:** Future Steam review refreshes still automatically re-sort their affected tables. Release-status moves alone retain the current figures but insert newly moved games at the appropriate position. Every proposed repository update is a ZIP containing changed files, plus a suggested commit message; never modify GitHub directly.

## Coming Soon release timing audit and column naming — October 16, 2026

- Renamed the Early Access table column from `End` to **`Est. End`**, leaving every data value and game row untouched. The earlier history below uses `End` when documenting past versions.
- Verified **all five Coming Soon entries** against Steam and official developer/publisher communications. `When` now displays a developer-provided release date or period if available, otherwise `n/a`. For a stated window/range, use its **upper/latest endpoint**; no `(planned)` or `(est.)` suffix in the game catalog. Public Early Access launch dates are valid as the first release date; private playtests and betas are not. Preserve source detail here, not in the reader-facing game table.
- Sort **Coming Soon by release timing descending**, latest announced timing first, unknown `n/a` last; preserve prior order for equal/unknown dates. The October 16 result is Outward 2, Modern Warfare 4, Light No Fire, Horizon Hunters Gathering, Guild Wars 3. For a year/quarter-only value, sort at that period's end without falsely adding day precision to its displayed date.
- No game was moved, added, or removed. Counts remain **73 Possible Games, 19 Early Access, 5 Coming Soon**. Neither Steam review data nor review-based sorting for Possible Games/Early Access was changed.

| Game | Previous When | Catalog When | Primary evidence / caveat |
| :--- | :--- | :--- | :--- |
| [Outward 2](https://store.steampowered.com/app/2849490/Outward_2/) | 2027 | **Feb 8, 2027** | [Nine Dots Studio, Oct 8, 2026](https://www.ninedotsstudio.com/news/outward-2-new-release-date), explicitly announced **PC Early Access on February 8**. The official announcement is in Oct 2026, therefore this is Feb **2027**. Steam can display **Feb 7** in some time zones. First public release is Early Access, not full 1.0. |
| [Call of Duty: Modern Warfare 4](https://store.steampowered.com/app/4435490/Call_of_Duty_Modern_Warfare_4/) | Oct 22 2026 | **Oct 23, 2026** | [Activision's release announcement, May 28, 2026](https://www.callofduty.com/blog/2026/05/call-of-duty-modern-warfare-4-announcement.html) says worldwide Friday **October 23**; the Steam page advertises **October 22** for its regional unlock. Preserve developer's stated global date per user preference. |
| [Light No Fire](https://store.steampowered.com/app/2719590/Light_No_Fire/) | TBA | **n/a** | [Steam listing](https://store.steampowered.com/app/2719590/Light_No_Fire/) says to be announced; [Hello Games](https://hellogames.org/news) has made no dated release commitment in the checked official announcements. |
| [Horizon Hunters Gathering](https://store.steampowered.com/app/4244910/Horizon_Hunters_Gathering/) | TBA | **n/a** | [Steam](https://store.steampowered.com/app/4244910/Horizon_Hunters_Gathering/) shows Coming soon; [Guerrilla's announcement](https://www.guerrilla-games.com/read/announcing-horizon-hunters-gathering) and later [playtest update](https://blog.playstation.com/2026/05/05/horizon-hunters-gathering-second-playtest-new-hunters-episode-region-revealed/) give no public release window. Playtests are not launches. |
| [Guild Wars 3](https://store.steampowered.com/app/4743930/Guild_Wars_3/) | TBA | **n/a** | [ArenaNet / NCSoft announcement, June 2026](https://about.ncsoft.com/en/news/article/nc_update_260606) announced a **fall 2027 beta**, not a public release. [Steam](https://store.steampowered.com/app/4743930) shows To be announced; do not equate the beta's date with the release date. |


## Coming Soon Early Access prefix — October 16, 2026

- **User-approved display:** In Coming Soon, put `EA ` before the `When` date/period **only when the first public game release is explicitly confirmed by the developer/publisher as an Early Access launch**. Examples: `EA Feb 8, 2027`, `EA Late 2027`. Otherwise keep the ordinary full-release date/period or `n/a` if no timing is known. For range-based dates, use only the latest endpoint as before.
- **Verified change:** **Outward 2** becomes `EA Feb 8, 2027`. Nine Dots Studio confirmed its first public release is PC Early Access on February 8; its announcement was dated October 8, 2026: https://www.ninedotsstudio.com/news/outward-2-new-release-date . Steam may display February 7 depending on time zone, but the developer-announced date governs.
- **Not Early Access:** **Call of Duty: Modern Warfare 4** remains `Oct 23, 2026` (developer-stated global full launch). Steam lists preorder **campaign** early access on Oct 16 and DMZ early access on Oct 20; these are advance game/mode access for buyers, **not a release into Steam Early Access**, so no `EA` prefix: https://store.steampowered.com/app/4435490/Call_of_Duty_Modern_Warfare_4/ .
- **Unknown timing:** Light No Fire, Horizon Hunters Gathering, and Guild Wars 3 stay `n/a`. A beta/playtest date does not qualify as a first public Early Access launch. Do not display `EA n/a`.
- **Sorting:** Continue sorting Coming Soon latest-first by the underlying announced calendar date or period, **ignoring `EA`**, with `n/a` last. This display change does not alter row order.
- **Scope:** Only the Outward 2 date marker and reader-facing explanation in `games/README.md` change; no game is transferred between sections. Steam review data and the other game tables are untouched. Root README instructions updated so new chats apply the same convention.

## Coming Soon ordering correction — October 16, 2026

- **Current authoritative rule (supersedes earlier latest-first notes above):** Sort `Coming Soon` in `games/README.md` by the next announced first-public-release date/period **ascending (soonest first)**. Place all unknown `n/a` values **last, alphabetically by game title** (case-insensitive). Preserve existing relative order for exact ties among known dates/periods.
- Ignore the `EA ` prefix for chronological sorting. Use the existing period-end convention for comparing dates that specify only a year, quarter, season, or month; **do not invent a specific day for display**. Keep the upper end of developer-announced date ranges in the catalog.
- **New order:** Call of Duty: Modern Warfare 4 (`Oct 23, 2026`), Outward 2 (`EA Feb 8, 2027`), Guild Wars 3 (`n/a`), Horizon Hunters Gathering (`n/a`), Light No Fire (`n/a`).
- No dates or Early Access markers were revised. No entries moved between sections; all game descriptions, links, and review figures are unchanged. This ordering rule is permanent and must be applied after every future Coming Soon date refresh. The previous latest-first order recorded above is **historical, not current guidance**.
- As always: GitHub is read-only for the assistant; changes are delivered as a ZIP with repository-relative paths and a suggested commit message for the owner to commit manually.

## Played worksheet import — October 16, 2026

- Imported the `Played` worksheet from `VaultNap Games List.xlsx` as the **fourth and final** section of `games/README.md`, **after Coming Soon**. There are **23 game rows**, corresponding to source rows **6–28**.
- The worksheet has two columns, **Game** and **Who**. Rows 1 and 3–5 were blank in Game (row 2 is the header), so those preliminary rows were excluded, as requested. Preserve the relative order of all 23 nonblank Game rows (no sorting) and the exact Who values (Tony, Errol, Steve).
- All 23 Game cells contain linked Steam storefront URLs; copied those hyperlinks to the new Markdown table without changing game titles, people, or links. No research, review refresh, new-game validation, deduplication or categorization was done.
- **Current layout:** 73 Possible Games, 19 Early Access, 5 Coming Soon (97 candidate rows), plus **23 Played entries**. Played is a historical list, not a fourth group of candidate games; games may appear in Played as well as elsewhere unless a later user-approved cleanup changes that.
- Because the current GitHub version still had the old Coming Soon sort, this ZIP is **cumulative** with the pending October 16 earliest-first sorting correction. The active rule is earliest first; unknown `n/a` titles last, alphabetized. Future assistants must use the current root README instructions and not historical latest-first notes above.
- **Standing workflow:** All changes are delivered as a ZIP of repository-relative files with a suggested commit message. GitHub is read-only for the assistant; the owner commits manually. If these conventions change, update this context and root README in the same ZIP.

## Played month/year dates — October 16, 2026

- The owner provided a `When` date for each of the **23 Played entries**. Added `When` as the final column after `Game` and `Who` and preserved all names, links, Who attributions and existing row order.
- Date format is **`MMM YYYY`** (e.g. `Sep 2026`). These months/years were **supplied by the owner**, not independently cross-checked against Steam. Do not infer they are exact first-launch timestamps or first group co-op session dates. For future changes, retain the user's supplied precision; avoid inventing days.
- No sorting of Played has been requested. Do not re-sort it when dates are changed unless explicitly instructed. Other catalog sections, review data, and release timelines were not modified.
- The 23 dates, keyed to the existing game rows, are recorded in `games/README.md`. They range from **Oct 2021** (Halo: The Master Chief Collection) to **Sep 2026** (Escape Simulator).
- Workflow continuity: Future repo edits still require a ZIP containing only changed repository files, plus a suggested manual commit message. GitHub remains read-only for assistants.

## Played sorting — October 17, 2026

- **Current authoritative rule:** Sort the `Played` table in `games/README.md` by the owner-supplied `When` month/year **descending (most recent first)**. Break ties alphabetically by game name, case-insensitively. Apply this sort automatically whenever Played dates or entries are updated. Earlier instructions preserving original worksheet row order and not sorting are superseded.
- Reordered all **23 Played rows** with their unchanged Game names, Steam links, `Who` values, and `When` dates. The sorting moves **Civilization VI, Elden Ring, Satisfactory, Destiny 2, and Torchlight II** into the appropriate positions; the rest retain their relative date grouping.
- `When` values retain `MMM YYYY` precision, are supplied by the owner, and should not be mistaken for independently verified Steam first-played dates. No changes to Possible Games, Early Access, or Coming Soon.
- **Delivery:** This update includes only the changed `games/README.md`, root `README.md` instruction, and this project-context file. The owner commits manually; GitHub access stays strictly read-only for assistants.

## Quick Description review — October 17, 2026

- Applied the user's approved wording changes to **47 Quick Descriptions**: **27 Possible Games**, **15 Early Access**, and **5 Coming Soon**. The other **50** candidate descriptions were left as originally recorded. The canonical updated wording is in `games/README.md`; do not automatically rephrase again in later chats.
- Style rule: favor concise, informative, neutral descriptions of the principal gameplay activity and distinguishing mechanics/setting, approximately **3–6 words** where practical. Avoid overly broad terms that make different games indistinguishable. Don't imply a game supports three-player co-op unless this has been separately confirmed.
- The change touches only description cells in the three candidate sections. **No game names, Steam links, Steam review percentages or counts, dates, order, section assignments, or Played history changed.** The review scores and release dates remain the previously recorded snapshots, not newly refreshed data.
- Multiplayer compatibility is **not** comprehensively audited. Separate follow-up research should verify party size and co-op mode before recommending a title for all three players.
- Repository collaboration is unchanged: read current root instructions at each new chat; deliver future proposed changes as a ZIP of changed files and a commit message; owner makes all GitHub commits manually.

## Update games command and refresh — October 17, 2026

- **Standing command defined:** When the owner says **`Update games`**, follow the complete, repeatable workflow in [`docs/UPDATE_GAMES.md`](UPDATE_GAMES.md) and the current root README: update reviews **and re-sort both review-bearing tables**, verify Early Access launch dates, present developer-stated or defensible upper-end `Est. End` periods, verify Coming Soon first-release timing and sort soonest-first with alphabetized unknowns. `Played` is out of scope. This runbook supersedes any earlier project notes limiting updates to one table at a time.
- **Review refresh, October 17:** Checked all **73 Possible Games** and **19 Early Access** Steam titles for all-time review data, using the English-language all-time review breakdown when Steam exposed it and otherwise the all-time overall figure. Applied the exact-integer-below-1,000 and one-decimal-`k`-at-or-above-1,000 display rule. Re-sorted each section by Percent descending and **exact** count descending. Underlying exact review totals, Steam app IDs and access caveats now appear in [`docs/REVIEW_SNAPSHOT.md`](REVIEW_SNAPSHOT.md). For age-gated pages, used recently indexed Steam store listing content, which may lag live figures; preserve this provenance instead of claiming identical real-time precision for all 92.
- **Notable rating movement:** `RuneScape: Dragonwilds` increased from **81% to 82%** and was moved into the 82% group in Possible Games. Several review counts moved slightly, including Firefighting Simulator: Ignite reaching **1,000**, now displayed `1.0k`. Most percentages remain unchanged. Exact counts are in the audit file; re-check before the next update.
- **Early Access timeline/status audit, October 17:** All **19 existing Early Access games** are still labeled Early Access by Steam, and previously recorded Start dates remain consistent. Found **no verifiable replacement** for the existing `Est. End` periods or `n/a` values; these were preserved without implying that duration-derived periods are firm developer release commitments. No EA game was moved. Source: each game's Steam Early Access page and associated developer notes. Note Sandustry is currently listed by Steam as single-player, so its three-person suitability remains separately unverified.
- **Coming Soon audit, October 17:** Checked all **five** entries. Current official first-release values remain `Call of Duty: Modern Warfare 4 — Oct 23, 2026` ([Activision](https://www.callofduty.com/blog/2026/05/call-of-duty-modern-warfare-4-announcement.html)), `Outward 2 — EA Feb 8, 2027` ([Nine Dots](https://www.ninedotsstudio.com/news/outward-2-new-release-date)), and `n/a` for Guild Wars 3, Horizon Hunters Gathering, Light No Fire. Preserved earliest-first sorting then alphabetized `n/a` rows. A playtest or beta announcement is not a release date. No Coming Soon game was reclassified.
- **Other status detail:** `Enshrouded` reached its full release on October 15, 2026 ([Steam](https://store.steampowered.com/app/1203620/Enshrouded/)), but was already in Possible Games, so no transfer was necessary.
- **Unchanged by this command:** All 23 Played rows and their dates, Quick Descriptions, game-name and Steam-link fields, and table structures. Section totals remain **73 Possible Games, 19 Early Access, 5 Coming Soon, 23 Played**.
- **Read-only/manual commit:** ZIP delivery with changed and new repository-relative files plus suggested commit message. Never commit or write to GitHub.

## Eight games removed from candidate lists — October 17, 2026

The owner explicitly requested removal of these **eight** games after a review of suitability for three people playing together on Windows 11 PCs. Remove them from `games/README.md` and **do not reintroduce them automatically** during `Update games`, future Steam-review refreshes, release-status transfers, or recommendations. Restoring a title requires the owner's explicit instruction. No games were removed from `Played`, which remains a historical record.

| Previous section | Removed game | Suitability concern discussed |
| :--- | :--- | :--- |
| Possible Games | Outward | Native campaign co-op limited to two (PC mods are optional and unsupported) |
| Possible Games | Star Trek: Bridge Crew | No longer readily purchasable on Steam; multiplayer access may have service limitations |
| Possible Games | Street Fighter 6 | One-on-one fighting, not simultaneous three-player co-op |
| Possible Games | Kiln | Team-based competitive PvP, rather than desired three-player co-op experience |
| Possible Games | Where Winds Meet | Some group activities exist, but much of the core story experience is solo |
| Early Access | Sandustry | Single-player listing; no verified native multiplayer |
| Early Access | Breathedge 2 | Single-player; cooperative multiplayer not planned |
| Coming Soon | Outward 2 | Announced native co-op supports two players |

- **Current candidate counts after removal:** 68 Possible Games, 17 Early Access, 4 Coming Soon = **89 candidates** (down from 97). `Played` remains **23**; total game rows across all four sections are **112**.
- No other row text, links, review figures, Early Access dates, release dates, or sorting criteria changed. `docs/REVIEW_SNAPSHOT.md` is a **dated historical record** of the October 17 review audit, not an active candidate table: it deliberately retains the removed games' old snapshot rows for auditability.
- Root README and `docs/UPDATE_GAMES.md` now explicitly protect owner exclusions; the assistant must never write to GitHub and must deliver ZIP + commit message for manual application.

## Full-release game discovery additions — October 18, 2026

- **Owner-approved:** Add **12** fully released native-online-co-op games to `Possible Games` only. New total: **80 Possible Games**, **17 Early Access**, **4 Coming Soon**, and **23 Played** (**101 candidates** and **124 combined rows**). No new entries in `Early Access`, `Coming Soon` or `Played`.
- **Review method:** Steam store **all-time English-language** percentage and exact count as read on October 18, 2026, except *Moving Out 2*, which shows only the **overall all-time** score on its Steam listing. Counts are rendered as exact integers below 1,000, otherwise one decimal `k` with half-up rounding. Insert new rows according to Percent descending and underlying exact Count descending. **Do not refresh existing games' review figures** as part of this addition; their existing October 17 snapshot is preserved. Existing candidate row order within ties was not altered.
- **Verification:** Each new entry was checked against its Steam storefront for full-release status, Windows PC support, Steam Online Co-op listing and a mode supporting three players. These are current store facts, not assurances of progression design or ease of play. Sources and precise measured values follow.

| New game | Steam app ID | Quick Description | Percent | Exact reviews | Scope |
| :--- | ---: | :--- | ---: | ---: | :--- |
| [Core Keeper](https://store.steampowered.com/app/1621690/Core_Keeper/) | 1621690 | Underground mining survival crafting | 94% | 23,869 | English |
| [Necesse](https://store.steampowered.com/app/1169040/Necesse/) | 1169040 | Settlement-building survival RPG | 94% | 12,610 | English |
| [ICARUS](https://store.steampowered.com/app/1149460/ICARUS/) | 1149460 | Planetary wilderness survival crafting | 77% | 31,651 | English |
| [The Lord of the Rings: Return to Moria](https://store.steampowered.com/app/2933130/The_Lord_of_the_Rings_Return_to_Moria/) | 2933130 | Dwarven underground survival crafting | 79% | 6,804 | English |
| [Starbound](https://store.steampowered.com/app/211820/Starbound/) | 211820 | Space exploration sandbox crafting | 88% | 51,873 | English |
| [Monster Hunter Rise](https://store.steampowered.com/app/1446780/MONSTER_HUNTER_RISE/) | 1446780 | Cooperative monster-hunting action RPG | 87% | 35,058 | English |
| [Warhammer 40,000: Darktide](https://store.steampowered.com/app/1361210/Warhammer_40000_Darktide/) | 1361210 | Sci-fi horde combat shooter | 76% | 75,210 | English |
| [Left 4 Dead 2](https://store.steampowered.com/app/550/Left_4_Dead_2/) | 550 | Cooperative zombie horde shooter | 97% | 234,220 | English |
| [GTFO](https://store.steampowered.com/app/493520/GTFO/) | 493520 | Hardcore tactical horror shooter | 88% | 25,766 | English |
| [Content Warning](https://store.steampowered.com/app/2881650/Content_Warning/) | 2881650 | Comedy horror filming adventure | 93% | 35,466 | English |
| [Unrailed!](https://store.steampowered.com/app/1016920/Unrailed/) | 1016920 | Cooperative railway-building survival | 94% | 4,677 | English |
| [Moving Out 2](https://store.steampowered.com/app/1641700/Moving_Out_2/) | 1641700 | Chaotic furniture-moving co-op | 72% | 468 | Overall |

- **Caveats:** *Monster Hunter Rise* has solo Village quests even though co-op Hub hunts support a trio. *GTFO* and *Warhammer 40,000: Darktide* are four-person-squad-oriented, but three friends can team together (with an AI/other player for the extra slot as applicable). These games were explicitly approved despite their differing modes/structure. No multiplayer mods are required for three people to play together.
- **Eight discovery suggestions declined by the owner (do not automatically re-suggest):**

| Game | Owner's reason |
| :--- | :--- |
| 7 Days to Die | Already played extensively |
| No Man's Sky | Already played extensively |
| Factorio | Already played extensively |
| Remnant II | Tried the first game; not a good group fit |
| For The King II | Similar turn-based group style did not fit (Civilization) |
| Baldur's Gate 3 | Too large a commitment |
| PEAK | Already tried; not a good group fit |
| PICO PARK 2 | Doesn't look like a good fit |

- These eight *declined discovery suggestions* are distinct from the eight titles previously **removed** from the candidate lists. Do not automatically reintroduce or re-suggest either set; user may explicitly override this later. Keep historical Played data unchanged.
- **Files/impact:** Updated `games/README.md` for the twelve rows and header provenance; updated root `README.md` to carry declined discovery suggestions forward; updated this project context with sources, raw review counts and preferences. Do not alter game names, reviews or dates of any existing rows, other table schemas, or `docs/UPDATE_GAMES.md`.

## ZIP packaging rule — October 18, 2026

- **Owner instruction (supersedes all earlier changed-files-only guidance):** Every future repository update ZIP must include **the complete set of Markdown documentation files** from the current repo, including unchanged files. Always include root `README.md` and `AGENTS.md`, `games/README.md`, every existing `docs/*.md` (including `docs/UPDATE_GAMES.md`, `docs/PROJECT_CONTEXT.md`, and `docs/REVIEW_SNAPSHOT.md`), plus any newly created documentation in the future. Include changed non-documentation files if needed. Respect the exact repository-relative paths.
- This archive **repackages the already-approved 12 fully released co-op game additions** from the immediately preceding update, rather than conducting another Steam review refresh. Starting from the latest GitHub state (68 Possible / 17 Early Access / 4 Coming Soon / 23 Played), it adds the same 12 titles to Possible Games to reach 80. All existing review figures, game links, descriptions, dates, and ordering rules are otherwise preserved. Avoid double-applying the additions if they have already been committed.
- The latest GitHub `docs/UPDATE_GAMES.md` was re-read and retained with its existing intentional-exclusion guidance, then only its packaging section was revised for the new rule. The latest GitHub `AGENTS.md` is included and its documentation handoff text is updated to reflect the new packaging rule.
- When this replacement package was prepared, `docs/REVIEW_SNAPSHOT.md` was restored from the October 17, 2026 Update games ZIP. **Subsequent documentation audit (October 18):** its active table was reconciled with all **97** current review-bearing games and the exact October 18 figures for the twelve additions; seven excluded games were moved into a historical-only table. The underlying review values were not refreshed in the audit; their separate October 17/18 check dates are preserved.
- ZIPs should be **merged into the existing repository root**, overwriting listed files as appropriate but not deleting entire folders. A documentation file being unchanged is not grounds to omit it. GitHub remains read-only to the assistant; only the owner commits.

## Documentation consistency audit — October 18, 2026

- Compared all **six** currently tracked Markdown files against the GitHub `main` file hashes; the latest repository matches the complete-documentation package from October 18.
- Reconciled `docs/REVIEW_SNAPSHOT.md` to the current active roster: **80 Possible Games + 17 Early Access = 97**, with no missing, duplicate, or differently formatted review figures. Added the **12 previously documented October 18 exact counts** and separated the **seven October 17 records for removed games** into historical-only records. No new Steam reviews were fetched and no prior percentages or counts were revised.
- Checked all active review rows against the snapshot for Steam app ID, section, percentage, exact count/rounding and ranking. The catalog's four tables total **80/17/4/23** and the two review-bearing tables are correctly sorted. Game data and `games/README.md` remain unchanged.
- Clarified the current-state handoff, the scope/date of snapshot observations, exclusion handling, mixed date provenance and the permanent **include-all-documentation** ZIP rule. Old notes remain intentionally historical; current instructions take precedence.
- All repository-relative documentation links were checked locally. No released-game status, multiplayer compatibility, Steam reviews or new Coming Soon dates were independently researched in this documentation-only audit.


## Early Access discovery additions — October 18, 2026

- **Owner-approved:** Add the **11** Early Access games below to the existing 17, producing **28 Early Access**, **80 Possible Games**, **4 Coming Soon**, and **23 Played** (**112 active candidates**, **135 total rows**). All 11 were checked against their official Steam Early Access listings on October 18, 2026. No existing game was moved, re-rated, or otherwise changed; Played and Coming Soon are untouched.
- **Steam reviews:** Added the eleven games' **all-time English-language** review Percent and exact review counts where Steam displayed an English summary, or the **all-time overall** review figures otherwise. Counts below 1,000 are exact; counts at least 1,000 round to one decimal `k` in the catalog. Sorted Early Access by percent descending, exact (unrounded) count descending for ties. Historical observations for the original 97 review-bearing games keep their October 17 or October 18 check dates. Added the new exact counts to `docs/REVIEW_SNAPSHOT.md`, yielding **108 active entries**.

| New game | App ID | Percent | Exact reviews | Scope | EA Start | Est. End | Source |
| :--- | ---: | ---: | ---: | :--- | :--- | :--- | :--- |
| [Phasmophobia](https://store.steampowered.com/app/739630/) | 739630 | 94% | 360,324 | English | Sep 18, 2020 | H2 2026 | [Steam](https://store.steampowered.com/app/739630/) |
| [Jump Space](https://store.steampowered.com/app/1757300/) | 1757300 | 87% | 8,422 | English | Sep 19, 2025 | 2027 | [Steam](https://store.steampowered.com/app/1757300/) |
| [Bellwright](https://store.steampowered.com/app/1812450/) | 1812450 | 79% | 10,507 | English | Apr 23, 2024 | 2027 | [Steam](https://store.steampowered.com/app/1812450/) |
| [Deep Rock Galactic: Rogue Core](https://store.steampowered.com/app/2605790/) | 2605790 | 69% | 7,623 | English | May 20, 2026 | May 2028 | [Steam](https://store.steampowered.com/app/2605790/) |
| [Everwind](https://store.steampowered.com/app/2253100/) | 2253100 | 81% | 1,738 | English | Mar 17, 2026 | n/a | [Steam](https://store.steampowered.com/app/2253100/) |
| [Lightyear Frontier](https://store.steampowered.com/app/1677110/) | 1677110 | 82% | 2,532 | English | Mar 19, 2024 | Nov 4, 2026 | [Steam](https://store.steampowered.com/app/1677110/) |
| [Sunkenland](https://store.steampowered.com/app/2080690/) | 2080690 | 83% | 9,117 | English | Aug 25, 2023 | n/a | [Steam](https://store.steampowered.com/app/2080690/) |
| [Craftopia](https://store.steampowered.com/app/1307550/) | 1307550 | 79% | 7,541 | English | Sep 4, 2020 | n/a | [Steam](https://store.steampowered.com/app/1307550/) |
| [Saleblazers](https://store.steampowered.com/app/1419850/) | 1419850 | 78% | 1,990 | Overall | Sep 29, 2023 | n/a | [Steam](https://store.steampowered.com/app/1419850/) |
| [Volcanoids](https://store.steampowered.com/app/951440/) | 951440 | 84% | 4,936 | English | Jan 29, 2019 | n/a | [Steam](https://store.steampowered.com/app/951440/) |
| [Echoes of Elysium](https://store.steampowered.com/app/2644050/) | 2644050 | 61% | 512 | Overall | Jan 27, 2026 | May 2027 | [Steam](https://store.steampowered.com/app/2644050/) |

- **Early Access target provenance and limitations:**
  - **Phasmophobia:** Steam EA Q&A: planned second half of 2026, provisional.
  - **Jump Space:** Steam store: Leaving Early Access in 2027; ignore stale ~5 month Q&A.
  - **Bellwright:** Developer Q&A: full release within three years of Apr 2024 EA launch (derived end-year, not fixed date).
  - **Deep Rock Galactic: Rogue Core:** Developer Q&A: 18–24 months in Early Access, May 2028 is derived upper endpoint.
  - **Everwind:** EA Q&A specifies at least one year only, minimum duration not an actionable target.
  - **Lightyear Frontier:** Steam Leaving Early Access banner scheduled Nov 4, 2026; still EA as of Oct 18.
  - **Sunkenland:** Old 1-year EA expectation expired in 2024; no credible current forecast.
  - **Craftopia:** Old minimum of 1 year, no current exit forecast; Steam score omits off-topic review activity.
  - **Saleblazers:** Old minimum of 2 years, no current exit forecast; Steam displays overall review scope.
  - **Volcanoids:** Original 2-year plan was extended; no actionable current exit forecast.
  - **Echoes of Elysium:** Developer Q&A: approx 12–16 months in EA; May 2027 is derived upper endpoint.
- **Review caveats:** Craftopia's Steam English rating explicitly excludes off-topic review activity. Saleblazers and Echoes of Elysium showed an all-time Overall review summary (not a separately labeled English score). No other active review snapshot figures were refreshed. All eleven sources are game-specific official Steam store pages; recorded October 18, 2026, with dynamic counts subject to change.
- **User-declined games (new exclusions; do not recommend or add without explicit request):** Lethal Company (tried; poor fit), Project Zomboid (played extensively), Nightingale (owner concerned development is abandoned), The Forever Winter (owner concerned about reception), Soulmask (owner concerned about reception), and Rogue Point (owner concerned about reception). The latter two had been mentioned as full-release alternatives, not part of the eleven Early Access additions. These six join the **eight earlier declined suggestions**, for **fourteen declined discoveries**, in addition to the **eight owner-removed candidates**. The comments about Nightingale's development and other games' reception are the owner's preferences, **not independently verified determinations** of their current status.
- **Continuity:** Do not automatically re-suggest any of the six declined titles, or reintroduce previously removed titles. Maintain the all-Markdown-files ZIP rule and GitHub read-only policy. Next `Update games` should re-check 1.0 transfers (especially Lightyear Frontier after November 4), ratings, and projected dates, rather than automatically classifying based only on a future target.

## Coming Soon discoveries and split commands — October 18, 2026

- **Owner instruction:** Add **all 17** Coming Soon recommendations from the preceding discovery, including **three previously marked tentative/watchlist** titles (BLACKFROST, Chrono Odyssey, The CUBE). This was an **explicitly approved selection**; new future `Find new games` runs must still seek approval before inserting their recommendations.
- Added 17, bringing **Coming Soon to 21**, **129 active candidates** (80 Possible Games, 28 Early Access, 21 Coming Soon), and **152 rows including the 23 Played entries**. No changes to the existing four Coming Soon rows, 108 review-bearing games, existing review figures, Early Access timelines, or Played history.
- Added the named **`Find new games`** command, with a [separate discovery runbook](FIND_NEW_GAMES.md), covering **all three candidate sections**. `Update games` remains a [maintenance-only command](UPDATE_GAMES.md) for **existing** catalog data and transfers already-listed titles only when verified release status changes. Discovery never silently adds games, nor does maintenance silently seek new titles. Record declines and owner exclusions before future discovery.
- **Review snapshot:** `docs/REVIEW_SNAPSHOT.md` remains *byte-for-byte unchanged*: Coming Soon has no `Percent`/`Count` fields. It still contains **108 active exact-count records and seven separately archived removed-game records** with their original observation dates. Do not pretend this discovery refreshed Steam ratings.
- **Sort:** Soonest known first; use the period's end for chronological sorting, then `n/a` alphabetical by title (case-insensitive). Known `2027`/`EA 2027` periods are sorted as the end of 2027, *after* `Nov 2027`, without implying a precise release date. An unknown EA launch shows `n/a`, **never** `EA n/a`.

| Added game | Steam app ID | When | Official source / special qualification |
| :--- | ---: | :--- | :--- |
| [State of Decay 3](https://store.steampowered.com/app/1340720/) | 1340720 | 2027 | Official developer 2027 target despite Steam TBA; shared world supports up to four; [source](https://www.stateofdecay.com/undead-labs-becomes-independent-studio/) |
| [Kingmakers](https://store.steampowered.com/app/2109770/) | 2109770 | n/a | Steam coming soon, co-op listed, no current usable release window; [source](https://store.steampowered.com/app/2109770/) |
| [Under a Rock](https://store.steampowered.com/app/1667040/) | 1667040 | n/a | Steam Coming Soon to Early Access; no published timing. 1–10 player support; [source](https://store.steampowered.com/app/1667040/) |
| [Den of Wolves](https://store.steampowered.com/app/1818140/) | 1818140 | n/a | Steam coming soon and online co-op; no announced first release date; [source](https://store.steampowered.com/app/1818140/) |
| [Blight: Survival](https://store.steampowered.com/app/1774880/) | 1774880 | n/a | Steam TBA; online co-op up to four; [source](https://store.steampowered.com/app/1774880/) |
| [Hela: of Mice & Magic](https://store.steampowered.com/app/3161310/) | 3161310 | Dec 1, 2026 | Steam store gives Dec 1, 2026; co-op for up to four; [source](https://store.steampowered.com/app/3161310/) |
| [Witchbrook](https://store.steampowered.com/app/1846700/) | 1846700 | 2026 | Steam listing currently states 2026; 4-player co-op; year-only date sorts by Dec 31; [source](https://store.steampowered.com/app/1846700/) |
| [JOIN US](https://store.steampowered.com/app/3401960/) | 3401960 | Mar 2027 | Developer changed 2026 EA/beta plan to full public release March 2027; do not use EA prefix; [source](https://steamcommunity.com/app/3401960/) |
| [GONE DIGGING](https://store.steampowered.com/app/4247230/) | 4247230 | EA Q2 2027 | Steam Coming Soon to Early Access, Q2 2027; 1–4 co-op; [source](https://store.steampowered.com/app/4247230/) |
| [Canyons](https://store.steampowered.com/app/2708860/) | 2708860 | Nov 2027 | Developer announced November 2027 release window Oct 8; co-op up to four; [source](https://steamcommunity.com/app/2708860/allnews/) |
| [Seaforge: Shores of Atlantis](https://store.steampowered.com/app/4712440/) | 4712440 | EA 2027 | Steam Coming Soon to Early Access 2027, 1–4 player co-op; [source](https://store.steampowered.com/app/4712440/) |
| [Streets of Rogue 2](https://store.steampowered.com/app/2165810/) | 2165810 | n/a | Developer Oct 6 update: no reliable Early Access launch date yet; no inference from old missed dates; [source](https://steamcommunity.com/app/2165810/announcements/) |
| [TROLLHEIM: GNOMES](https://store.steampowered.com/app/4139890/) | 4139890 | n/a | Steam Coming Soon to Early Access; Steam does not provide usable launch timing; co-op advertised up to eight; [source](https://store.steampowered.com/app/4139890/) |
| [ARK 2](https://store.steampowered.com/app/2050420/) | 2050420 | n/a | Steam announces initial Early Access release but has no current launch date; online co-op advertised; [source](https://store.steampowered.com/app/2050420/) |
| [BLACKFROST: The Long Dark 2](https://store.steampowered.com/app/1586260/) | 1586260 | EA 2027 | Steam confirms planned Early Access in 2027; three-person party size not yet independently verified; [source](https://store.steampowered.com/app/1586260/) |
| [Chrono Odyssey](https://store.steampowered.com/app/2873440/) | 2873440 | n/a | Steam advertises MMO and online co-op; party size and shared progression details unverified; [source](https://store.steampowered.com/app/2873440/) |
| [The CUBE](https://store.steampowered.com/app/3230430/) | 3230430 | n/a | Steam advertises MMO/co-op without confirmed fixed trio party mechanics; Windows requirements are still TBA; [source](https://store.steampowered.com/app/3230430/) |

- **High-priority verification:** BLACKFROST advertises co-op but does not yet confirm a three-person maximum; Chrono Odyssey is an MMO with online co-op but cooperative party progression has not been established; The CUBE lists co-op/MMO but does not confirm fixed-party mechanics. These were added because the owner said to add **all** suggestions, not because the concerns had been resolved. Recheck before recommending an actual purchase/session.
- **Developer-source exceptions:** State of Decay 3's 2027 target is supported by the developer's [September 22, 2026 statement](https://www.stateofdecay.com/undead-labs-becomes-independent-studio/), while the Steam page still says TBA. Canyons' November 2027 timing comes from the [October 8 developer announcement](https://steamcommunity.com/app/2708860/allnews/). JOIN US' developer [announced a March 2027 **full release**](https://steamcommunity.com/app/3401960/), replacing a prior beta/EA idea; **no EA prefix**. GONE DIGGING, Under a Rock, Seaforge, BLACKFROST, and TROLLHEIM show *Coming Soon to Early Access* on Steam. Streets of Rogue 2's developer confirmed an EA-first plan but intentionally **has no reliable date**. ARK 2's official Steam description promises an initial EA release, but no timeframe.
- **Provenance:** Lookups are current as of October 18, 2026. Store listings and developer dates are planning information, not guarantees of eventual launch; no playable demo or closed beta counts as first public release. Normal Steam store availability and three-player features can change before launch.

## Approved individual-game updates applied — October 26, 2026

- **Applied and cleared all four approved items** from the root README handoff queue. These approvals came from individual game discussions and are applied here on the owner's explicit request; they do **not** represent another full-catalog `Update games` Steam refresh. Check the root README's Pending updates section for future queues; it is now empty.
- **Possible Games additions:** [over the hill](https://store.steampowered.com/app/2929250/over_the_hill/) (app `2929250`), `Cooperative off-road exploration adventure`, **94% / 2,665 all-time English reviews** (catalog `2.7k`); [Trash Day](https://store.steampowered.com/app/3314580/Trash_Day/) (app `3314580`), `Physics-based raccoon scavenging adventure`, **96% / 712 all-time Overall reviews** (catalog `712`). Both launched in October 2026, are fully released, and list online co-op that supports a trio. Source: Steam store pages, observed **October 26, 2026**. Rating counts can change.
- **Played transfer:** [Palworld](https://store.steampowered.com/app/1623730/) moved out of Possible Games and into Played with owner-supplied `Who = Steve` and `When = Oct 2026`; existing Steam link retained. Placed at the top of Played as newest. Its prior Possible Games review record (95%, exact 184,376 English all-time reviews, checked Oct 17) was removed from the **active** review snapshot and kept in a **separate moved-to-Played historical table**, not classified as an owner exclusion.
- **Discovery source:** [Co-Optimus](https://www.co-optimus.com/) is an additional source for investigating Possible Games and multiplayer support, as already specified in `docs/FIND_NEW_GAMES.md`. Steam and developer/publisher sources remain the authority for release status, exact review data and announced features. Co-Optimus access may vary.
- **Post-change counts:** 81 Possible Games, 28 Early Access, 21 Coming Soon, 24 Played (**130 candidate rows; 154 rows overall**). Snapshot: **109 active exact-review records**, seven rejected/removed historical records, **one** transfer-to-Played historical record. Previous observations of unaffected games were preserved, not silently redated.
- **Workflow for future individual approvals:** Do not make a ZIP for individual-game discussion. Queue approved additions/transfers for the next requested repository update or the next full `Update games` run, then verify, deduplicate, apply and clear. This exception allows already-approved additions during maintenance but never authorizes unrequested game discovery. `Find new games` still proposes candidates for approval first.
- **Packaging and access:** Include every existing Markdown document, even unchanged files, plus any changed non-Markdown files, in the ZIP. GitHub is strictly read-only to the assistant; owner applies and commits manually.

## What has not been checked yet

- **Steam reviews:** The 84 continuing October 17 games retain that check date; 12 Possible Games and 11 Early Access additions retain October 18, 2026; two more Possible Games were checked October 26, 2026. `docs/REVIEW_SNAPSHOT.md` holds exact counts for all **109** active review-bearing games plus seven excluded historical entries and Palworld’s separately archived Played transfer. No all-game refresh occurred on October 18; Coming Soon reviews are not tracked.
- **Early Access dates/status and Coming Soon dates:** All 21 original Early Access entries were audited October 16, 2026; Smalland and Solarpunk were moved to Possible Games, leaving 19 Early Access entries at the time (17 after the subsequent owner-approved removals). All 5 then-listed Coming Soon entries had release timing rechecked October 17, 2026. Eleven newly added Early Access titles and 17 new Coming Soon titles were checked on October 18, 2026; the four carried-over Coming Soon dates were not independently rechecked in this addition. Dates in Possible Games have not been audited; developer windows and exact dates can change and need rechecking.
- **Three-player compatibility** was reviewed preliminarily on October 17, 2026, and eight unsuitable or unwanted candidates were removed; 12 owner-approved fully released three-player co-op games and 11 Early Access games were added October 18. A complete mode-by-mode audit of the currently active **130 candidates** has **not** been performed. Being listed does not guarantee every mode supports three-player co-op.
- **Descriptions:** 47 descriptions were revised October 17, 2026 using the approved concise gameplay-focused wording. Remaining descriptions retain their original wording; comprehensive external fact-checking and three-player validation are still pending. Non-Steam availability has not been independently reviewed. Possible Games and Early Access are sorted by review metrics, not recommendation rank.
- All four source worksheets have now been imported; `Played` was added after the three candidate sections. Historical counts above describe the earlier three-section baseline.

## New-chat handoff and queued approvals — October 26, 2026

- Added a concise copyable **Continue this project in a new ChatGPT chat** prompt directly below the title in root `README.md`. The prompt points to the latest root instructions, `AGENTS.md`, `games/README.md` and all `docs/*.md`, and reinforces strict read-only GitHub access, complete-documentation ZIPs, and owner-only commits. Do not paste large historical instructions into the prompt; the latest repo is the authority.
- **Approved but not applied:** Add `over the hill` (Steam app `2929250`) and `Trash Day` (`3314580`) to Possible Games on the next `Update games`, using fresh Steam all-time reviews, exact counts and correct ranking. Proposed Quick Descriptions: `Cooperative off-road exploration adventure` and `Physics-based raccoon scavenging adventure`. The owner explicitly approved both individual games without requesting ZIPs at the time.
- **Approved but not applied:** Move `Palworld` (`1623730`) from Possible Games to Played, with **Who = Steve** and **When = Oct 2026**, preserving its Steam link, sorting Played newest first, moving its active review record to the historical-only snapshot, and refreshing review data for other active games as requested by `Update games`.
- **Approved discovery source:** Use [Co-Optimus](https://www.co-optimus.com/) when finding candidate Possible Games and checking multiplayer capabilities, while cross-validating with Steam/developer information. This is a source addition, not a candidate game.
- **Workflow exception:** User requested that approved individual-game proposals not generate ZIPs. Queue them until the next `Update games` and apply there, even though normal `Update games` does **not** discover new games. `Find new games` still proposes rather than adding automatically. Clear the queue once committed; never add queued titles twice.
- **Scope of this October 26 package:** Documentation only; all 80 Possible, 28 Early Access, 21 Coming Soon, 23 Played entries and 108 active review snapshot rows remain unchanged pending a future full refresh. All seven Markdown documentation files are included (including unchanged ones) for manual extraction into the existing repo. GitHub was not modified by the assistant.

## Future workflow

The owner will point future chats at `https://github.com/IrishStevo/vaultnap`. The assistant should read the latest root README instructions, these notes, the Update games runbook, the Find new games runbook, the review snapshot, and the current game list. Agree on specific changes in chat; prepare a ZIP of **all Markdown documentation files, changed and unchanged**, plus any changed non-documentation files. Provide a suggested commit message. Merge into the existing repo; **do not make GitHub changes through a connector or API**. The owner commits manually.

When the requested data review begins, work in user-directed steps rather than replacing the entire list or imposing new ranking/column schemes without approval. Record consequential decisions and completed checks here after the user decides to include them in a repo update.
