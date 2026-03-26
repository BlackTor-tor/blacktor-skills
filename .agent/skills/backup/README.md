# Backup Skills

This category contains skills related to backup, snapshot, sync, and recovery workflows.

## Included skills

### openclaw-git-backup

Location:

- `.agent/skills/backup/openclaw-git-backup/`

Purpose:

- create or maintain scheduled git backup workflows for OpenClaw repositories
- commit only real changes
- summarize added/modified/deleted files in commit messages
- push backups to a remote repository
- exclude scheduler noise when needed

## Category rules

New backup-related skills should:

- live under `.agent/skills/backup/`
- use one folder per skill unless the skill is intentionally file-only
- include `SKILL.md` when the skill has behavior, scripts, or references
- place runnable helpers under `scripts/`
- place supporting documents under `references/`
- use names that describe the workflow directly
