---
allowed-tools: Bash(./scripts/wt:*)
argument-hint: create <branch> | list | remove <branch> | clean | open <branch>
description: Manage git worktrees with automated setup
---

Manage git worktrees using the `./scripts/wt` script with arguments: $ARGUMENTS

Operations:
- **create <branch>**: Create worktree with automated setup (copies .env files, runs pnpm install) and opens in new code editor window `code $WORKTREE_DIR`
- **list**: Show all current worktrees
- **remove <branch>**: Remove an existing worktree
- **clean**: Clean up stale worktrees
- **open <branch>**: Open the worktree in new code editor window `code $WORKTREE_DIR`

Execute the appropriate `./scripts/wt` command and confirm the result.