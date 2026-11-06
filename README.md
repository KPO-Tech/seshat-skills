# seshat-skills

Skills written for Seshat itself. Automatically installed at first boot and updated in the background, so they are available without any manual setup.

Public, third-party skills (code review, debugging, documents and so on) are not kept here: Seshat offers them by default and downloads them from their own sources, with their updates.

## Skills

None for now. The page base for HTML artifacts moved into the system prompt of SeshatOS (ADR 0024), where it costs no extra reads.

## Structure

```
seshat-skills/
├── <skill-name>/
│   ├── SKILL.md          # required: frontmatter + instructions
│   ├── assets/           # optional: files the skill copies or adapts
│   ├── references/       # optional: extended docs, read on demand
│   └── scripts/          # optional: executable utilities
```

Skills are installed to `.seshat/skills/repos/seshat-skills/` and updated in the background (at most once per hour).

## Credits and Licenses

No third-party content is kept here at the moment.

This repository is released under the MIT License, see [LICENSE](LICENSE).
