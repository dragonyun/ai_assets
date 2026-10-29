---
name: hello-world
description: >-
  A minimal demo skill that greets the user and explains how TeamAI skills are
  structured. Use when the user says "hello", "hi", "demo skill", or asks how
  TeamAI skills work.
---

# hello-world

This is a minimal TeamAI skill used to explore how skills are organized,
versioned, and synced across a team repo.

## What it does

When triggered, this skill simply explains its own structure so you can see
where files live and how they flow through `teamai push` / `teamai pull`.

## File locations

| Location | Purpose |
|----------|---------|
| `.claude/skills/hello-world/SKILL.md` | Local Claude Code copy |
| `.github/skills/hello-world/SKILL.md` | Local GitHub Copilot copy |
| `.qoder/skills/hello-world/SKILL.md` | Local Qoder copy |
| `.trae/skills/hello-world/SKILL.md` | Local Trae copy |
| `ai_assets/skills/hello-world/SKILL.md` | Canonical team-repo copy |

## Next steps

1. Edit this skill locally.
2. Run `teamai push` to publish the change.
3. Run `teamai status` to see the diff.
4. Run `teamai pull` on another machine to sync it down.
