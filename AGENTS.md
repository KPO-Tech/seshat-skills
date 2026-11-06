# seshat-skills: Agent Instructions

This repository contains the skills written for Seshat itself. It is automatically cloned by Seshat at first boot and updated in the background. Public skills from other projects do not belong here: Seshat downloads those from their own sources.

## Skill format

Each top-level directory is one skill:

- `SKILL.md`: required entry point (frontmatter with `name` and `description`, then instructions)
- Optional subdirectories: `agents/`, `assets/`, `references/`, `scripts/`

Companion files referenced from `SKILL.md` are loaded on demand; they are not skills themselves.

## Contributing

- Every skill must have a `SKILL.md` with valid YAML frontmatter (`name`, `description`)
- Keep `SKILL.md` under 500 lines; put extended content in `references/`
- Skills must work without network access during execution
- Do not add platform-specific hooks or bootstrap scripts
- Credit every third-party source and its licence in the README
