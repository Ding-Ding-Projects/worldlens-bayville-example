# Roadmap

## Repository closeout

- [x] Fetch the remote and inventory the primary checkout.
- [x] Inventory linked worktrees, branches, stashes, refs, and recoverable Git objects.
- [x] Confirm there are no uncommitted paths, unresolved index entries, or conflict markers.
- [x] Create and verify the required external archive before any removal decision.
- [x] Record preservation, archive, integration, and cleanup evidence in `HANDOFF.md`.
- [ ] Complete remote issue and discussion synchronization when the GitHub CLI is usable; currently blocked because the issue-list command did not return a usable result.
- [x] Dew the documentation commit and verify `refs/heads/main` with `git ls-remote` at `235580df91d81f294d9992afa3dfe704285a4289`.

## Explicit exclusions

- No release or installer work.
- No changes to other repositories or blocked families.
- No new linked worktrees, task sessions, or pigs.
- No removal, because no safe redundant linked worktree, non-default branch, or stash was discovered.
