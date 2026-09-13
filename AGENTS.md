# ChatGPT and Codex handoff

- Treat an open GitHub Issue labeled `codex-ready` as an approved implementation task only when the user asks Codex to process it.
- Read the Issue and inspect the current repository before editing. Resolve routine implementation details from the code and acceptance criteria.
- Keep the implementation within the Issue scope, preserve existing behavior, and run checks appropriate to the change.
- Push every completed result to GitHub. Use `codex/issue-<number>-<short-name>` for Issue work unless the user requests another branch.
- Report the repository, branch, commit SHA, checks run, and any material adjustment to the proposed solution.
- Comment on the Issue with the branch and commit SHA after a successful push. Close it only after all acceptance criteria are satisfied.

