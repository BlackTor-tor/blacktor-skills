# SKILL.md Metadata Convention

Use a short frontmatter block at the top of `SKILL.md`.

## Minimum recommended fields

```yaml
---
name: your-skill-name
description: Short description of what the skill does and when to use it.
---
```

## Field rules

### name

- should match the skill folder name when possible
- use lowercase kebab-case
- keep it stable after publication if external references may exist

### description

- short and specific
- say what the skill does
- say when to use it
- avoid vague wording like "general helper"

## Optional metadata

Add more fields only when they clearly help the repository or downstream tooling.

Examples:

- `version`
- `tags`
- `owner`
- `status`

Do not add noisy metadata that nobody will maintain.
