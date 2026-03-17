# AI Workflow Starter Kit
**Free tools for non-technical builders using Claude Code.**

Two files. Ten minutes to set up. You'll never start a session from zero again.

---

## What's in here

| File | What it does |
|------|-------------|
| `claude-md-template.md` | A project memory file Claude reads automatically every session — your rules, decisions, and context, persistent across every conversation |
| `creative-brief-skill.md` | A slash command that runs a structured 5-question brief before any build session — so Claude builds what you actually mean, not what it assumes |

---

## File 1 — CLAUDE.md Template

### What it is
Claude Code reads a `CLAUDE.md` file automatically every time you open a project. It's your persistent brief — hard rules, design language, decisions log, what's next. Without it, every session starts from zero. With it, Claude picks up exactly where you left off.

### How to install
1. Copy `claude-md-template.md` into your project's root folder
2. Rename it to `CLAUDE.md` (exactly — capital letters, no extension change)
3. Open it and replace every `[bracketed placeholder]` with your actual project info
4. Save it — Claude Code will read it automatically from now on

### How to fill it out
- **Hard Rules** — the non-negotiables. Be specific. "No dark backgrounds" is better than "keep it light." "Primary color is #FF4713 — never substitute" is better than "use orange."
- **Design Language** — describe the visual identity in words Claude can act on. Name fonts, hex codes, and what the aesthetic should *feel* like.
- **Decisions Log** — every time you make a call, log it here immediately. Don't wait. This is what prevents you from relitigating the same conversation next session.
- **What's Next** — keep this current. At the start of each session, tell Claude: "Read CLAUDE.md and start with item 1."

### Tips
- The more specific your Hard Rules, the better your output
- Log decisions as you make them — not at the end of the session
- If Claude violates a rule, correct it *and* rewrite the rule to be more explicit
- Update this file every session — it gets more valuable over time

---

## File 2 — /creative-brief Skill

### What it is
A skill file is a reusable slash command for Claude Code. This one runs a structured 5-question brief before any build session — capturing what you're building, what it's for, what to avoid, and the one detail that separates "close enough" from "yes, that's it." Claude confirms its understanding before writing a single line of code.

### How to install
1. Find or create the skills folder on your machine:
   ```
   ~/.claude/skills/
   ```
   On Mac, `~` means your home folder (`/Users/yourname/`). You may need to create the `skills` folder if it doesn't exist yet.

2. Copy `creative-brief-skill.md` into that folder
3. Rename it to `creative-brief.md`
4. Restart Claude Code (or open a new session)

### How to use it
In any Claude Code session, type:
```
/creative-brief
```
Claude will ask you five questions. Answer them. It'll confirm its understanding back to you before building anything. If it's off, correct it before it starts — not after.

### When to use it
- At the start of any new build session
- Before adding a major feature or screen
- Any time you feel like Claude is building the generic version of your idea instead of your version

---

## GitHub
All files are available at: [github.com/yourusername/ai-workflow-starter-kit](https://github.com)

---

*From the newsletter at drewmartinez.io — Issue 03, Series 1 of 2*
