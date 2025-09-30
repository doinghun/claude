---
allowed-tools: Bash(./scripts/wt:*)
argument-hint: create <branch> | list | remove <branch> | clean
description: Manage git worktrees with automated setup
---

Manage git worktrees using the `./scripts/wt` script with arguments: $ARGUMENTS

Operations:
- **create <branch>**: Create worktree with automated setup (copies .env files, runs pnpm install)
- **list**: Show all current worktrees
- **remove <branch>**: Remove an existing worktree
- **clean**: Clean up stale worktrees

Execute the appropriate `./scripts/wt` command and confirm the result.