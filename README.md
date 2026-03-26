# blacktor-skills

Public skills repository for BlackTor.

## Repository layout

This repository stores skills under a fixed path convention:

- `.agent/skills/<category>/<skill-name>/`

Examples:

- `.agent/skills/backup/openclaw-git-backup/`
- `.agent/skills/coding/code/codeview.md`

A skill may be either:

- a folder containing `SKILL.md`, scripts, references, and related files
- a standalone file when the skill is intentionally lightweight

## Current categories

- `backup`

See `.agent/skills/README.md` for the skills index.

## Adding a new skill

When uploading a new skill to this repository, follow these rules:

1. Put it under `.agent/skills/<category>/`
2. Prefer one dedicated folder per skill
3. Use lowercase kebab-case for folder names
4. Keep scripts under `scripts/`
5. Keep references or notes under `references/`
6. Put the main spec in `SKILL.md` when it is a full skill
7. Use a single markdown file only for very lightweight skills
8. Update `.agent/skills/README.md`
9. Update the category README such as `.agent/skills/backup/README.md`

## Naming rules

- category: short, generic, lowercase
- skill name: lowercase kebab-case
- avoid spaces
- avoid machine-specific names unless they are intentionally product-specific
