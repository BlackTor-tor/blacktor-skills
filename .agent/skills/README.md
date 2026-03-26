# Skills Index

## Path convention

Skills are stored as:

- `.agent/skills/<category>/<skill-name>/`
- or `.agent/skills/<category>/<parent>/<child-file>` when a lightweight file layout is preferred

## Upload standard

For every new skill added to this repository:

- choose a clear category
- prefer one folder per skill
- use lowercase kebab-case names
- store executable helpers in `scripts/`
- store supporting docs in `references/`
- include `SKILL.md` for full skills
- update this index
- update the corresponding category README

## Categories

### backup

- `openclaw-git-backup` — scheduled git backup workflow for OpenClaw repositories

See `./backup/README.md` for category details.

## Helpers

- `./CHECKLIST.md` — pre-push checklist for new skills
- `./CATEGORIES.md` — suggested category naming guide
- `./_templates/README.md` — starter templates for new skills
- `./METADATA.md` — `SKILL.md` frontmatter convention
- `./REVIEW.md` — review standard before pushing new skills
