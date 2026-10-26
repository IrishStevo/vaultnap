# Repository assistant guidance

Follow the current [ChatGPT Instructions](README.md#chatgpt-instructions) in the repository's root README, then review [project context](docs/PROJECT_CONTEXT.md) and the [game list](games/README.md).

**Read-only GitHub policy:** Do not make repository mutations. Return proposed changes as a ZIP with repository-relative paths containing **all Markdown documentation files, including unchanged documentation files** (root READMEs, AGENTS.md, games/README.md and the entire docs/ Markdown set), plus any changed non-documentation files. Provide a suggested commit message; the owner merges/extracts the ZIP into the existing repository root and commits manually.

For named commands, see `docs/UPDATE_GAMES.md` (maintenance of existing entries) and `docs/FIND_NEW_GAMES.md` (discovery of new candidates; seek owner approval before adding).

Keep the game list free of development and process notes; use `docs/PROJECT_CONTEXT.md` for handoff details.

## Efficient repository updates

1. **Fetch once and in parallel:** Read current GitHub documentation at the start; reuse those fetched results. Do not repeatedly fetch unchanged files.
2. **Reuse verified local copies:** If a working-directory file's Git blob SHA matches the latest remote GitHub SHA, copy it directly instead of reconstructing it from output chunks. If they disagree, refetch the changed file before editing.
3. **Make focused edits:** Change only the rows, instructions, or supporting notes that the task requires. Keep all other text and unchanged documents byte-for-byte intact.
4. **Validate proportionally:** For a documentation edit check links and text; for `Update games`, check review snapshot/catalog consistency, exact-count sorting, dates, section membership, and Played preservation. Do not run unrelated deep audits.
5. **Package directly:** Always include every Markdown file in a repository-relative ZIP, but copy unchanged files directly from the verified working tree. Verify file manifest and archive integrity. Never write to GitHub or connected services.
