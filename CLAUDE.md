A homebrew D&D 5E compendium for realistic modern combat, used as a reference during pen-and-paper play sessions. Content lives under `modern-warfare-5e/`, which is also the folder opened as an Obsidian vault.

## Layout

- `README.md`, `LICENSE` - project description, attribution, licensing. Attribution lives **only** here, never inside `modern-warfare-5e/`.
- `modern-warfare-5e/home.md` - master Map of Content.
- `modern-warfare-5e/<section>.md` - section landing pages (MOCs) that link into their sibling folders.
- `modern-warfare-5e/<section>/<file>.md` - content files. Max nesting depth is 2 under `modern-warfare-5e/`.

## Editing rules

- Every content file starts with YAML frontmatter: `title`, `aliases`, `tags`.
- Filenames are kebab-case, lowercase, and unique across the whole vault (Obsidian resolves wikilinks by name).
- Cross-file links use standard markdown, not wikilinks: `[Shaken](../rules/conditions.md#shaken)`.
- Intra-file links use heading anchors: `[Triage Code](#triage-code)`.
- Use regular hyphens (`-`), never em-dashes or en-dashes.
- Do not add attribution or license notices inside `modern-warfare-5e/`.

## Adding content

- A new designation goes in `modern-warfare-5e/designations/<name>.md` and gets a link in `modern-warfare-5e/combat-designations.md`.
- A new weapon category goes in `modern-warfare-5e/weapons/<name>.md` and gets a link in `modern-warfare-5e/weapons.md`.
- Keep section landing pages as pure link indexes plus a short intro - no rules content.
