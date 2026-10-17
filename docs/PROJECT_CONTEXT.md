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

## What has not been checked yet

- **Steam reviews:** Possible Games and Early Access review figures refreshed October 16, 2026; review data for Coming Soon is not tracked.
- **Early Access dates/status and Coming Soon dates:** All 21 original Early Access entries were audited October 16, 2026; Smalland and Solarpunk were moved to Possible Games, leaving 19 Early Access entries. All 5 Coming Soon entries had their release timing audited on October 16, 2026. Dates in Possible Games have not been audited; developer windows and exact dates can change and need rechecking.
- **Three-player compatibility**, play modes, dedicated servers, and other gameplay suitability details have **not** been audited. Being listed does not guarantee a game supports three players in co-op.
- **Descriptions and non-Steam availability** have not been independently reviewed. Possible Games and Early Access are sorted by review metrics, which is not a recommendation ranking.
- The other worksheets in the original spreadsheet were intentionally **out of scope** for this first version.

## Future workflow

The owner will point future chats at `https://github.com/IrishStevo/vaultnap`. The assistant should read the current root README instructions, these notes, and the current games list. Agree on specific changes in chat; prepare a ZIP of only the files that should be added/replaced, accompanied by a suggested commit message. **Do not make GitHub changes through a connector or API.** The owner commits manually.

When the requested data review begins, work in user-directed steps rather than replacing the entire list or imposing new ranking/column schemes without approval. Record consequential decisions and completed checks here after the user decides to include them in a repo update.
