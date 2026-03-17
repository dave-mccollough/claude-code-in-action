# Hooks

- Run a command before or after Claude Code does something

- Run a code formater after Claude edits a file
- Stop Claude from edting or reading a file
- Check for TODO comments
- Run tests after a file has been changed
- Block file edits that add variable names that don't follow naming conventions
- Block deprecated function usage

- PreToolUse Hooks
  - Runs before tool is used
- PostToolUse Hool
  - Runs after took is used

- Hooks are defined in the following files
  - Global
    - `~/.claude/settings.json`
  - Project
    - `.claude/settings.json`
  - Project (not commited)
    - `./claude/settings.local.json`

- Hooks can be written by hand or by using `/hooks` command