# Set up Claude business prompts

You are installing this kit on the user's machine. Paths that don't start with `~` are relative to this repo.

## 1. Install the skills

If the user named one skill (admin-jobs, customer-messages, review-replies or talk-once), install only that one. Otherwise install all four.

Copy each chosen folder from `skills/` to `~/.claude/skills/<name>/`, replacing an older copy of the same skill if one is there. Create `~/.claude/skills/` if it's missing.

If Codex is installed (`~/.codex` exists), copy the same folders to `~/.codex/skills/<name>/` as well.

Change nothing else.

## 2. Check

Each installed `SKILL.md` exists and matches this repo's copy (and the Codex copy, if you made one).

## 3. Report

Tell the user, briefly, which skills are installed and where, and give one example ask for each, such as "draft a quote from these notes", "reply to this review", "turn this memo into my four jobs" or "draft the reminder text for tomorrow's job".

## Removing

Delete the skill folders from `~/.claude/skills/` (and `~/.codex/skills/` if present).
