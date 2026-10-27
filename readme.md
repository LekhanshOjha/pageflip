# Pageflip

An agent skill that writes and audits landing pages built to convert. Works with Claude Code, Codex, Cursor, Gemini CLI, GitHub Copilot, and any agent that supports the open Agent Skills (`skill.md`) format.

---

## Quick install (any agent)

```bash
npx skills add lekhanshojha/pageflip
```

This detects which coding agents you have installed and puts the skill in the right folder for each.

## Manual install

Download `skill.md` and put it in a `pageflip` folder inside your agent's skills directory.

| Agent | All projects (global) | One project only |
|---|---|---|
| Claude Code | `~/.claude/skills/pageflip/` | `.claude/skills/pageflip/` |
| Codex | `~/.agents/skills/pageflip/` | `.agents/skills/pageflip/` |
| Cursor | `~/.cursor/skills/pageflip/` | `.cursor/skills/pageflip/` |
| Gemini CLI | `~/.gemini/skills/pageflip/` | `.gemini/skills/pageflip/` |
| GitHub Copilot (VS Code) | `~/.copilot/skills/pageflip/` | `.github/skills/pageflip/` |

**One-line example (Claude Code, global):**

```bash
mkdir -p ~/.claude/skills/pageflip && curl -o ~/.claude/skills/pageflip/skill.md https://raw.githubusercontent.com/lekhanshojha/pageflip/main/skill.md
```

For another agent, swap `~/.claude/skills` for that agent's path from the table.

> Tip: `.agents/skills/pageflip/` in your project root is read by several agents (Codex, Gemini CLI, Copilot), so it's a good default if you switch between tools.

Restart your agent after installing, then ask it which skills are available to confirm Pageflip is listed.

## Use it

Ask your agent, for example: *"Write a landing page for my product"* or *"Audit our landing page."*

Before writing any copy, it creates an empty `audience-voice.md` in your project. Dump raw audience data into it: posts, comments, reviews, support emails, call notes, anything. No format needed.

The agent reads it, finds the patterns itself, and saves what it learned to `audience-insights.md`. The page copy is built from that.