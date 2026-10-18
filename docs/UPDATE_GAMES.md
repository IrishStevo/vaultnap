# Update games — repeatable maintenance command

When the owner says **“Update games”**, complete the following workflow using the latest `README.md`, `games/README.md`, and `docs/PROJECT_CONTEXT.md` from `IrishStevo/vaultnap`. Do not ask the user to repeat the steps. GitHub is **read-only**; return changed files as a ZIP, together with a suggested commit message.

## 1. Steam reviews: Possible Games and Early Access

1. Extract Steam app IDs from each existing game URL. Look up **all-time** Steam user-review positive percentage and underlying **exact review count**, preferring the **English-language** all-time review summary when separately exposed; otherwise use the all-time overall summary. Do **not** substitute Recent Reviews (past 30 days), a lifetime purchase or player count, or a stale secondary website number. Use the Steam listing and record when a figure is from a recently indexed Steam page because an age gate prevents direct reading. If a current number cannot be reliably verified, keep the existing value and flag the gap; do not fabricate one.
2. Show the original integer count if **below 1,000**; for **1,000 and above**, express thousands to **one decimal** using normal **half-up rounding**, including e.g. `1,250 → 1.3k` and `1,000 → 1.0k`.
3. Sort **each** updated review-bearing section by **positive Percent descending**, then **underlying exact review count descending** for percentage ties. Never use the abbreviated `k` value to break ties. Store the exact totals in `docs/REVIEW_SNAPSHOT.md` for future audits and re-sorting.
4. Update each section's review snapshot date in its explanatory line. Preserve `Game` links, Quick Descriptions, all Early Access Start/Est. End values, and unrelated columns except for changes independently established in later steps.

## 2. Early Access timelines and status

- Verify each title's current status and **actual Steam Early Access launch date** (`Start`) against Steam or an official announcement. Distinguish this from its eventual 1.0 release date.
- `Est. End` represents the latest developer/publisher-stated 1.0 timing (specific date, month, quarter, season, or year). Where the developer specifies an expected Early Access *duration*, derive only a justifiable broad period from the confirmed Start. For any range, show **only the later/upper end**. Leave `n/a` for absent, expired, minimum-only or unreliable targets. Do not add `(est.)`/`(planned)` suffixes to the reader-facing table; document source, underlying range, certainty and inference in `docs/PROJECT_CONTEXT.md`.
- If a title left Early Access for full release, move it to **Possible Games** and insert it into the rating/count sort using the retained or newly refreshed review metrics. Do not duplicate entries. Do not move games merely because they are already playable in Early Access.

## 3. Coming Soon release dates

- Check Steam and official developer/publisher updates for each game's **first public release**; private tests, betas, demos, and limited preorder access do **not** qualify.
- Show a concise exact date or developer-stated period in `When`, and use the **latest endpoint** of a published range. When first public release is explicitly planned as Early Access, prepend `EA ` (e.g. `EA Feb 8, 2027`, `EA Late 2027`); otherwise do not. If no current release period is confirmed, use `n/a`, **not** `EA n/a`. Prefer official worldwide dates to regional Steam unlock dates; document discrepancies.
- Sort **soonest first** by underlying calendar date/period, ignoring the `EA ` prefix; `n/a` rows must come **last, alphabetical by game title**. Compare coarse periods by the *end* of that period without pretending to know an exact day in the displayed table. Preserve the prior relative order for exact ties.
- If a Coming Soon game has actually entered Early Access or fully released, verify its status and move it to the appropriate table **only with source-supported review fields**; never make up missing ratings. Document any exception where review fields cannot be established.
- **Respect intentional exclusions:** Do not reintroduce games the owner deliberately removed, even if Steam review numbers, release status, or multiplayer features change. Read the current exclusion decisions in `docs/PROJECT_CONTEXT.md` first; restoration requires an explicit new owner request. Historical `docs/REVIEW_SNAPSHOT.md` rows are not candidate-list membership.

## 4. Preserve historical Played data

- Preserve all `Played` Game, Who, When values, Steam links and existing ordering (When newest first, alphabetical ties) unless the user explicitly requests a Played change. Do not refresh Played reviews or infer historical play dates.

## 5. Documentation, packaging and handoff

- Update `docs/REVIEW_SNAPSHOT.md` with actual counts (not rounded) and source/scope or unresolved caveats. Update `docs/PROJECT_CONTEXT.md` with the run date, date/status findings, notable review-score movements, any transfers and remaining uncertainties.
- Keep the canonical `games/README.md` clean and reader-facing. Keep the top-level ChatGPT Instructions and this runbook correct as workflow preferences change.
- Compare current files against the latest GitHub state. Package **the complete Markdown documentation set (changed and unchanged)**, preserving repository-relative paths: root `README.md` and `AGENTS.md`, `games/README.md`, and **all** files in `docs/`, notably this runbook and `docs/REVIEW_SNAPSHOT.md`. Include any changed non-documentation files as necessary. Never deliver a changed-files-only ZIP. If a previously expected documentation file is missing from GitHub, identify and explicitly explain any restoration rather than silently omitting it. Ask the owner to extract/merge the ZIP into their existing repository, **not** replace whole directories. Provide a suggested commit message. **Never use GitHub write actions**, even if connector permissions allow it.
