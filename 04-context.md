# Context

- Codebase Context

- `/init` Command
  - Scans codebase
  - Creates a summary
  - Creates and writes a summary to the `CLAUDE.md` file
    - This summary is included in every request

- `CLAUDE.md` file
  - Guides Claude through your codebase
    - Important commands
    - Architecture
    - Coding style
  - Allows you to give Claude specific directions
  - Three different types of `CLAUDE.md` files
    - `CLAUDE.md`
      - Generated with `/init` command
      - Commited to source control
      - Shared with other team members
    - `CLAUDE.local.md`
      - Not shared with other team members
      - Contains personal instructions or customizations for Claude
    - `~/.claude/CLAUDE.md`
      - Used with all projects on machine
      - Contains instructions you want to Claude to follow on all projects

- Using `#` character
  - Puts Claude in memory mode 
  - Prompts where you want instruction saved

- Using `@` character
  - Mention specific file
    - `@ + path to file`
  - Points Claude to a specific file

