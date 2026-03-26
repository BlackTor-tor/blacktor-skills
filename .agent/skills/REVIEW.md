# New Skill Review Standard

Before merging or pushing a new skill, review it for safety and repository hygiene.

## Safety review

Check that the skill does not include:

- API tokens
- passwords
- cookies
- private keys
- personal access tokens
- machine-specific credential files
- secrets embedded in examples

## Portability review

Check for accidental machine-specific details such as:

- absolute local paths like `/root/...`
- private emails
- local usernames
- hostnames
- device-specific assumptions that should be configurable instead

## Structure review

Check that:

- the path follows repository convention
- naming follows lowercase kebab-case where appropriate
- `SKILL.md` exists for full skills
- scripts are in `scripts/`
- supporting docs are in `references/`
- indexes are updated

## Quality review

Check that:

- the description is specific
- the skill has a clear purpose
- steps are actionable
- examples do not leak private context
- documentation matches the actual file layout

## Final rule

Do not publish a skill just because it works locally.
It must also be safe to share, understandable to others, and cleanly structured.
