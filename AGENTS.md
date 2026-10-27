# Repository assistant guidance

Follow the current [ChatGPT Instructions](README.md#chatgpt-instructions) in the repository's root README, then review [project context](docs/PROJECT_CONTEXT.md) and the [game list](games/README.md).

**Read-only GitHub policy:** Do not make repository mutations. Return proposed changes as a ZIP with repository-relative paths containing **all Markdown documentation files, including unchanged documentation files** (root READMEs, AGENTS.md, games/README.md and the entire docs/ Markdown set), plus any changed non-documentation files. Provide a suggested commit message; the owner merges/extracts the ZIP into the existing repository root and commits manually.

For named commands, see `docs/UPDATE_GAMES.md` (maintenance of existing entries) and `docs/FIND_NEW_GAMES.md` (discovery of new candidates; seek owner approval before adding).

Keep the game list free of development and process notes; use `docs/PROJECT_CONTEXT.md` for handoff details.

## Efficient repository updates

1. **Use the read-only GitHub connector by default; fetch once and in parallel:** Read the current GitHub documentation with the connector at the start, record blob SHAs, and reuse those fetched results. Do not repeatedly fetch unchanged files or attempt direct container downloads as a prerequisite.
2. **Reuse verified local copies:** If a working-directory file's Git blob SHA matches the latest remote GitHub SHA, copy it directly instead of reconstructing it from output chunks. If they disagree, refetch the changed file before editing.
3. **Make focused edits:** Change only the rows, instructions, or supporting notes that the task requires. Keep all other text and unchanged documents byte-for-byte intact.
4. **Validate proportionally:** For a documentation edit check links and text; for `Update games`, check both the review and 30-day popularity snapshot/catalog consistency, exact-count sorting, dates, section membership, and Played preservation. Do not run unrelated deep audits.
5. **Package directly:** Always include every Markdown file in a repository-relative ZIP, but copy unchanged files directly from the verified working tree. Verify file manifest and archive integrity. Never write to GitHub or connected services.

## Default GitHub connector workflow and offline ZIP packaging

**Default approach for every repository task:** Read the latest authoritative GitHub content using the available **read-only GitHub connector** (such as `fetch_file`) and record Git blob SHAs. Do not first try direct shell/Python downloads of `raw.githubusercontent.com` or GitHub archives. Those downloads are optional, not a prerequisite or a preferred first step. Never use GitHub write, commit, push, or PR actions.

**Why:** On October 26, 2026, direct requests from the file-building environment failed with DNS/network restrictions while the GitHub connector continued to work. A failed direct download does **not** mean GitHub content is unavailable or that local ZIP creation is impossible. Do not repeatedly retry a failing network path.

1. **Read from the source of truth.** Use the read-only GitHub connector as the primary access route, reading current repository instructions and documentation and recording each blob SHA. Check the latest GitHub version on each new task, even when a local archive is available.
2. **Reuse existing verified local bytes.** Check whether the working directory or a ZIP produced earlier in this conversation already contains each current file. Verify every candidate's Git blob SHA against the *current* GitHub connector result, not just its filename or prior date. The SHA for raw bytes is `sha1(b"blob " + str(len(data)).encode() + b"\0" + data)`. If a SHA matches, safely reuse those bytes without another download. If it differs, obtain the new bytes via the read-only connector.
3. **Bridge to local files only when needed.** When there is no matching local copy, use a supported in-session transfer method to put connector-returned content into the working environment. Verify decoded size and Git blob SHA; preserve original newline bytes. Do not assume a connector result or displayed attachment automatically created a local file. **Before attempting a substantial manual, custom-encoded, or multipart transfer, apply the technical-detour checkpoint below; do not silently start one.**
4. **Make a complete ZIP offline.** Once files exist locally, make the requested focused edits, and use Python's `zipfile` (or an equivalent local archiver) to include **every current repository Markdown documentation file**, preserving repo-relative paths, plus any changed non-Markdown files. Compare the archive manifest with the GitHub directory listing, verify unchanged files still match their original Git blob SHAs, reopen the ZIP, and run `testzip()` or equivalent integrity checks.
5. **Only then report success.** Confirm that the exact downloadable path exists and the archive opens before linking to it. Give a suggested manual commit message and tell the owner to merge/extract into the existing repository root. If neither the read-only connector nor valid local source bytes can be obtained, explain the limitation and ask for an upload instead of inventing a ZIP or guessing its contents.

### Stop before a substantial technical detour — owner's standing instruction

If an unexpected technical problem would require a **large unplanned detour** (for example, repeated failed tool calls, lengthy manual/encoded file transfers, complicated environment repairs, or an improvised multi-step workaround), **stop before starting that detour and tell the owner**. Explain what failed, the effect on the requested task, the proposed workaround and its complexity, and simpler options. Ask whether to proceed with the detour or take another approach. Do not quietly spend extensive effort on a workaround. A straightforward, already-known read-only connector read or verified-local-file reuse is the **normal process** and does not require asking first.

If the owner has not approved the large detour, do not undertake it; provide any reliably completed work and describe the remaining limitation without claiming the task is finished. The user's decision about how to handle the technical detour takes precedence over troubleshooting momentum.

This is the **default read-only access and packaging procedure**, not permission to mutate any connected service, reuse stale game data, skip fresh verification where required, or change the full-documentation ZIP rule.
