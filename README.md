# Modern Warfare 5E Compendium

A markdown edition of the *Modern Warfare (5E D&D)* homebrew compendium - a realistic-modern-combat conversion of the
Dungeons & Dragons 5th Edition rules.

## About this repository

This repository contains a transcription of the original compendium, with structure normalized for markdown (headings,
tables, lists, cross-references) and with further edits and adjustments made by me on top of that base.

- **Original author:** Killbodies0313
- **Original source:** <https://www.gmbinder.com/share/-MDbF8cyWo5BA-obmIkf>
- **Original publication:** © 2020, via GM Binder
- **This edition:** transcribed to markdown and subsequently edited by [Schwaggot](https://github.com/Schwaggot)

## Reading the compendium

The compendium lives under [`modern-warfare-5e/`](./modern-warfare-5e/home.md). Start at [
`modern-warfare-5e/home.md`](./modern-warfare-5e/home.md) for a table of contents, or jump straight to a section:

- [Character Creation](./modern-warfare-5e/character-creation.md)
- [Operator Class](./modern-warfare-5e/operator-class.md)
- [Combat Designations](./modern-warfare-5e/combat-designations.md)
- [Training Programs](./modern-warfare-5e/training-programs.md)
- [Weapons](./modern-warfare-5e/weapons.md)
- [Armor](./modern-warfare-5e/armor.md)
- [Gear](./modern-warfare-5e/gear.md)
- [Rules](./modern-warfare-5e/rules.md)

Open the `modern-warfare-5e/` folder as an Obsidian vault for in-session lookup, or browse it on GitHub.

The compendium is also published as a static site at
**<https://schwaggot.github.io/mw-5e-compendium/>** (English + German).

## Publishing the site

The site is built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) and the
[`mkdocs-static-i18n`](https://github.com/ultrabug/mkdocs-static-i18n) plugin. Python dependencies are
managed with [uv](https://docs.astral.sh/uv/) via `pyproject.toml`.

### Automatic deploys

Every push to `main` triggers
[`.github/workflows/gh-pages.yml`](./.github/workflows/gh-pages.yml), which builds the site with
`mkdocs gh-deploy` and force-pushes the output to the `gh-pages` branch. GitHub Pages serves that
branch at the URL above.

To force a fresh rebuild without a content change, go to
**Actions -> Deploy MkDocs to GitHub Pages -> Run workflow**.

The `gh-pages` branch is a build-output branch - do not check it out or commit to it manually.

### Local preview

```bash
uv sync
uv run mkdocs serve
```

Open <http://127.0.0.1:8000/mw-5e-compendium/>. Changes to markdown files, `mkdocs.yml`, and
`modern-warfare-5e/stylesheets/extra.css` live-reload.

### Adding German translations

For each English file, add a sibling `<name>.de.md` in the same directory. Untranslated pages fall
back to the English version automatically. Translated heading anchors should be preserved as
`## Translated Heading {#original-english-slug}` so cross-file links keep resolving.

## What has changed from the original

- The original GM Binder document was transcribed into markdown and then split into topic files under
  `modern-warfare-5e/`.
- Layout-specific formatting from GM Binder has been replaced with standard markdown constructs (tables, lists,
  headings, block quotes).
- Editorial notes have been added in a few places where the source text appears to contain typos or inconsistencies (for
  example, the armor proficiency entries for some Combat Designations). These notes are marked inline in italics.
- Spelling, wording, and minor phrasing have been adjusted in places for clarity. Rules content is intended to match the
  original in substance.
- Additional classes, skills, features, weapons, items etc. have been added.
- Weight units have been converted from lbs to the metric system (kg).

## Licensing

This project is a derivative work. See [`LICENSE`](./LICENSE) for the full notice. In short:

- The underlying compendium text is © 2020 Killbodies0313 and is redistributed here under fair-use / fan-content
  assumptions, with full attribution to the original author and source.
- The editorial changes, markdown structure, and annotations contributed by this repository's maintainer are released
  under
  the [Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).
- *Dungeons & Dragons* and *D&D* are trademarks of Wizards of the Coast LLC. This is unofficial fan content permitted
  under fair use; it is not approved or endorsed by Wizards of the Coast.

If you are the original author and would like attribution adjusted or the document removed, please open an issue on this
repository.
