# Pageflip

An agent skill that writes and audits landing pages built to convert. Works with Claude Code, Codex, Cursor, Gemini CLI, GitHub Copilot, and any agent that supports the open Agent Skills (`SKILL.md`) format.

📖 **How it works, the 6 conversion rules, and examples:** [Read the full post on Medium](MEDIUM_LINK_HERE)

---

## Quick install (any agent)

```bash
npx skills add YOUR_GITHUB_USERNAME/pageflip
```

This detects which coding agents you have installed and puts the skill in the right folder for each.

## Manual install

Download `SKILL.md` and put it in a `pageflip` folder inside your agent's skills directory.

| Agent | All projects (global) | One project only |
|---|---|---|
| Claude Code | `~/.claude/skills/pageflip/` | `.claude/skills/pageflip/` |
| Codex | `~/.agents/skills/pageflip/` | `.agents/skills/pageflip/` |
| Cursor | `~/.cursor/skills/pageflip/` | `.cursor/skills/pageflip/` |
| Gemini CLI | `~/.gemini/skills/pageflip/` | `.gemini/skills/pageflip/` |
| GitHub Copilot (VS Code) | `~/.copilot/skills/pageflip/` | `.github/skills/pageflip/` |

**One-line example (Claude Code, global):**

```bash
mkdir -p ~/.claude/skills/pageflip && curl -o ~/.claude/skills/pageflip/SKILL.md https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/pageflip/main/SKILL.md
```

For another agent, swap `~/.claude/skills` for that agent's path from the table.

> Tip: `.agents/skills/pageflip/` in your project root is read by several agents (Codex, Gemini CLI, Copilot), so it's a good default if you switch between tools.

Restart your agent after installing, then ask it which skills are available to confirm Pageflip is listed.

## Use it

Ask your agent, for example: *"Write a landing page for my product"* or *"Audit our landing page."*

It will create an `audience-voice.md` file in your project for you to fill with real customer quotes before it writes any copy.