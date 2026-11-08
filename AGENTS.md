# Repository assistant guidance

Follow the current [ChatGPT Instructions](README.md#chatgpt-instructions) in the repository's root README, then review [project context](docs/PROJECT_CONTEXT.md) and the [game list](games/README.md).

**Read-only GitHub policy:** Do not make repository mutations. Queue small documentation and ad hoc changes without automatically packaging; **every `Update games` command automatically delivers a ZIP**, while other tasks require an explicit owner request for packaging. In every ZIP, include **every repository file**, changed or unchanged, with original repository-relative paths, plus a suggested commit message. The owner merges/extracts the ZIP into the existing repository root, reviews, commits and pushes manually.

For named commands, see `docs/UPDATE_GAMES.md` (maintenance of existing entries) and `docs/FIND_NEW_GAMES.md` (discovery of new candidates; seek owner approval before adding).

Keep the game list free of development and process notes; use `docs/PROJECT_CONTEXT.md` for handoff details. For every `Update games`, **report in chat** section moves, popularity-star gains/losses and `n/a` transitions, and all **changed** Early Access `Start`/`Est. End` and Coming Soon `When` dates; omit routine review fluctuations. See `docs/UPDATE_GAMES.md` §6.

## Efficient repository updates

1. **Use the read-only GitHub connector by default; fetch once and in parallel:** Read the current GitHub documentation with the connector at the start, record blob SHAs, and reuse those fetched results. Do not repeatedly fetch unchanged files or attempt direct container downloads as a prerequisite.
2. **Reuse verified local copies:** If a working-directory file's Git blob SHA matches the latest remote GitHub SHA, copy it directly instead of reconstructing it from output chunks. If they disagree, refetch the changed file before editing.
3. **Make focused edits:** Change only the rows, instructions, or supporting notes that the task requires. Keep all other text and unchanged documents byte-for-byte intact.
4. **Validate proportionally:** For a documentation edit check links and text; for `Update games`, check both the review and 30-day popularity snapshot/catalog consistency, exact-count sorting, dates, section membership, and Played preservation. Do not run unrelated deep audits.
5. **Package automatically for `Update games`:** Each `Update games` command includes a ZIP and suggested commit message, without a separate request. For smaller documentation and other ad hoc changes, wait for the owner to request packaging. Every ZIP includes **all repository files**, changed or unchanged, preserving relative paths; verify the archive manifest and integrity. Never write to GitHub or connected services.

## Default GitHub connector workflow and offline ZIP packaging

**Default approach for every repository task:** Read the latest authoritative GitHub content using the available **read-only GitHub connector** (such as `fetch_file`) and record Git blob SHAs. Do not first try direct shell/Python downloads of `raw.githubusercontent.com` or GitHub archives. Those downloads are optional, not a prerequisite or a preferred first step. Never use GitHub write, commit, push, or PR actions.

**Why:** On October 26, 2026, direct requests from the file-building environment failed with DNS/network restrictions while the GitHub connector continued to work. A failed direct download does **not** mean GitHub content is unavailable or that local ZIP creation is impossible. Do not repeatedly retry a failing network path.

1. **Read from the source of truth.** Use the read-only GitHub connector as the primary access route, reading current repository instructions and documentation and recording each blob SHA. Check the latest GitHub version on each new task, even when a local archive is available.
2. **Reuse existing verified local bytes.** Check whether the working directory or a ZIP produced earlier in this conversation already contains each current file. Verify every candidate's Git blob SHA against the *current* GitHub connector result, not just its filename or prior date. The SHA for raw bytes is `sha1(b"blob " + str(len(data)).encode() + b"\0" + data)`. If a SHA matches, safely reuse those bytes without another download. If it differs, obtain the new bytes via the read-only connector.
3. **Stop on file-transfer blockers.** If current files cannot be made available in the local working environment by a straightforward supported method, **stop and tell the owner**. Ask them to upload a current repository ZIP rather than attempting custom encoding, multi-part transfers, repeated failed downloads, or other elaborate bridges. After an upload, verify file integrity and compare to the latest read-only GitHub blob SHAs.
4. **Make a complete ZIP offline after every `Update games` run, or when expressly requested for other tasks.** Once verified files exist locally, apply focused edits and use a local archiver to include **all repository files**, not just Markdown, preserving paths. Compare archive manifest to the current repository tree, preserve unchanged bytes and file names, reopen the ZIP, and test its integrity.
5. **Only report ZIP success after verification.** For an automatic `Update games` ZIP or an explicitly requested ZIP, confirm the exact downloadable path exists and the archive opens before linking it. Provide a suggested manual commit message. If source bytes are not readily available, stop, explain the blocker, and request an owner-provided fresh repository ZIP.

### Technical blockers — owner checkpoint

If a **technical issue prevents completing a requested step** (especially accessing repository files, getting them into the working environment, or creating an owner-requested ZIP), **stop and tell the owner promptly** what failed and how it blocks the task. Ask for guidance or a fresh upload of the repository ZIP rather than silently attempting elaborate troubleshooting, custom file-transfer encodings, or lengthy unplanned workarounds. Do not keep retrying the same failed network path.

Use good judgment: ordinary missing data, routine source age gates, code mistakes or documentation typos that can be handled directly are not reasons to interrupt the owner. The checkpoint applies to actual technical blockers, not every small correction. Proceed with verified routine work and honestly label any unavailable game facts as `n/a` or unchanged as the runbook requires.

**Repository packaging rule:** Each `Update games` command **always** includes a complete ZIP and a suggested manual commit message. For smaller documentation and other ad hoc updates, queue changes and **wait for an explicit packaging request**. Every ZIP contains **all repository files**. Keep the README's copyable new-chat prompt and `docs/PROJECT_CONTEXT.md` up to date.

This is the **default read-only access and packaging procedure**, not permission to mutate any connected service, reuse stale game data, skip fresh verification where required, or change the complete-repository ZIP rule and automatic `Update games` exception.
