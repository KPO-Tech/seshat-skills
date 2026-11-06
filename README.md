# seshat-skills

Skills written for Seshat itself. Automatically installed at first boot and updated in the background, so they are available without any manual setup.

Public, third-party skills (code review, debugging, documents and so on) are not kept here: Seshat offers them by default and downloads them from their own sources, with their updates.

## Skills

| Skill | Description |
|---|---|
| `html-page` | HTML artifacts only (a page shown in the Seshat preview); other design work uses the public skills: base page, design rules, chart/diagram/3D snippets, inline SVG icons |

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

`html-page` is original work, with these third-party parts:

- `html-page/references/design-rules.md`: rules adapted from the [Open Design](https://github.com/nexu-io/open-design) craft notes (Apache-2.0), themselves adapted from refero_skill (MIT).
- `html-page/references/icons.md`: 141 icons from [IconPark](https://github.com/bytedance/IconPark) (Apache-2.0, ByteDance), rendered as inline SVG with `currentColor`.

Apache-2.0 text: https://www.apache.org/licenses/LICENSE-2.0

This repository is released under the MIT License, see [LICENSE](LICENSE).
