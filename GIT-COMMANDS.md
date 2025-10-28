# Git Commands Extension

This extension provides commands to streamline your Git workflow.

## Commands

### `commit`

Generates a commit message from staged changes and commits it.

**Usage:**

This command is triggered when you want to commit your staged changes.

**Process:**

1. Reviews staged changes using `git diff --staged`.
2. Reviews the recent commit history using `git log -n 10` to match the commit message style.
3. Generates a commit message based on the changes and history.
4. Commits the staged changes with the generated message using `git commit`.
5. Checks the repository status after the commit using `git status`.
