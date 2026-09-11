# Screenshots

Highlight screenshots for atelier's independent-project pages, one folder per
project (folder name matches the atelier content filename, e.g.
`marginalia/`, `bedtime-premiere/`).

Served publicly via jsDelivr:
`https://cdn.jsdelivr.net/gh/dtduong30/rich-content@master/screenshots/<slug>/<file>`

**Adding screenshots for a new project:** don't follow manual steps here —
use the `add-project-screenshots` Claude Code skill
(`atelier/.claude/skills/add-project-screenshots/SKILL.md`), which captures,
names, places, and wires up the frontmatter automatically. This file exists
just as a pointer so the convention isn't duplicated in two places.

**Convention, for reference:**
- One folder per project slug.
- Numeric-prefixed filenames fix carousel order (`01-home.png`,
  `02-feature.png`, ...).
- PNG, captured at a 1440×900 desktop viewport.
