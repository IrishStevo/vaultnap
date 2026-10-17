# VaultNap

A place to keep track of games that three friends might play together on **Windows 11 gaming PCs**. We mostly use Steam, but other PC storefronts are fine when a game isn't available there.

## Game shortlist

**[Browse the game list →](games/README.md)**

| Section | Meaning |
| :--- | :--- |
| [Possible Games](games/README.md#possible-games) | Games we consider ready to play together |
| [Early Access](games/README.md#early-access) | Games in Early Access that might benefit from more development before we play |
| [Coming Soon](games/README.md#coming-soon) | Games not yet released, including into Early Access |

The shortlist is a set of **candidates**, not a verified list of games supporting three-player co-op. Platform support, player counts, release status, and store review numbers may need checking before we choose a game.

## How updates work

The owner makes all repository commits manually. Proposed updates are discussed in chat and delivered as a **ZIP archive of changed repository files**, plus a suggested **commit message**. Extract the ZIP at the repository root, inspect the changes, and commit them yourself. The assistant may **read** the repository but must never write to GitHub.

## ChatGPT Instructions

These instructions are the authoritative starting point for any new chat about this repository. **Re-read the latest version from GitHub at the beginning of a repo-related task**, rather than relying solely on previous conversation context or cached copies. Also read [docs/PROJECT_CONTEXT.md](docs/PROJECT_CONTEXT.md) for the current project state, and [games/README.md](games/README.md) for the actual game entries.

1. **Scope.** Help three friends shortlist and assess games to play together on Windows 11 gaming PCs. Prefer Steam listings where available, but games from other PC storefronts are acceptable. The group enjoys survival/crafting games and generally plays about three hours a week; treat these as preferences, not strict filters.
2. **Source of truth.** `games/README.md` is the canonical list of candidate games. Its three sections have the meanings above. Do not assume a game's placement is objectively correct without verification; it records our current assessment.
3. **Preserve data unless requested otherwise.** Don't silently add or remove titles, alter descriptions, move games between sections, change columns, re-sort rows, or overwrite existing fields when making unrelated updates. If a requested update calls for such changes, make them explicitly and describe them.
4. **Verify time-sensitive facts.** When asked to refresh reviews, release statuses/dates, multiplayer capabilities, or store links, consult up-to-date primary sources (Steam store pages and official publisher/developer information where possible). Distinguish verified facts from assumptions. Never invent review counts, percentages, dates, or player limits.
5. **Keep the game catalog clean.** `games/README.md` is reader-facing. Don't put drafting history, migration notes, to-do lists, assistant instructions, or chat commentary there. Use `docs/PROJECT_CONTEXT.md` for project progress, decision history, and pending data checks.
6. **GitHub is read-only for the assistant.** Never create, update, delete, commit, push, open PRs, or change branches/tags in the GitHub repository, even if write tools are technically available. Only the owner applies changes.
7. **Changes are delivered as ZIP + commit message.** For every task proposing repository edits, produce a downloadable ZIP with paths relative to the repository root (containing changed/new files only), and suggest a clear commit message. Do not commit changes yourself. State what changed and what was deliberately left unchanged. For questions or reviews that don't require file changes, no ZIP is necessary.
8. **Update continuity notes.** When a repo update changes the project workflow, schema, assumptions, completed work, or next steps, update `docs/PROJECT_CONTEXT.md` in the same proposed ZIP. Keep this root instruction section accurate as the working agreement evolves.
9. **Be deliberate about future schema changes.** The initial game tables retain the spreadsheet's existing column names. `Possible Games` now has an explicitly approved sort order (see item 10); otherwise, avoid unrequested table, column, section, or sorting changes. Suggest improvements separately before implementing them unless expressly asked to proceed.
10. **Possible Games sorting and Steam review formatting.** Maintain `Possible Games` in **descending Percent**, then **descending actual (unrounded) Steam review count** for games with equal Percent. The `Count` shown in Markdown is exact below 1,000 and displayed in `k` to one decimal place with normal (half-up) rounding at or above 1,000. Sort using the underlying exact counts, never the abbreviated displayed values. Reapply the sort after future Possible Games review refreshes. Keep other sections in their existing order unless instructed otherwise.
