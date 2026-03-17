# CLAUDE.md

This file gives Claude persistent context across sessions so you never start from zero.
Place it in your project's root folder. Claude Code reads it automatically every time you open the project.

Update it as your project evolves — especially the Decisions Log and What's Next sections.

---

## What This Is

**Project name**: [Your project name]
**One-liner**: [What it does in one sentence]
**Who it's for**: [Your target user — be specific]
**Stage**: [Idea / Prototype / MVP / Live]

---

## Hard Rules

These are non-negotiable. Claude must follow them in every session without exception.

- [Design rule — e.g., "No dark backgrounds unless I explicitly ask for one"]
- [Visual rule — e.g., "No emojis anywhere in the UI"]
- [Brand rule — e.g., "Primary color is #FF3210 — never substitute another red"]
- [UX rule — e.g., "No close buttons on modals — swipe or tap outside to dismiss"]
- [Copy rule — e.g., "Never use the word 'seamless' or 'streamlined' in any copy"]

Add as many as you need. The more specific, the better.

---

## Design Language

Define the visual and tonal identity here. Claude uses this to make decisions when you haven't specified something explicitly.

**Typography**:
- Display: [Font name, weight, size rule — e.g., "Helvetica Neue, weight 300, tight tracking"]
- Body: [Font name — e.g., "DM Sans, regular"]

**Color tokens**:
- Primary: [Name] — [hex] — [when to use it]
- Secondary: [Name] — [hex] — [when to use it]
- Background: [Name] — [hex]
- Text: [Name] — [hex]
- Border: [Name] — [hex]

**Aesthetic in words**: [e.g., "Swiss editorial — white space is structural, hairline borders only, no shadows, no gradients, no fills in table cells"]

**What it must never look like**: [Name a reference you want to avoid — e.g., "Not TikTok. Not any generic SaaS dashboard."]

---

## Decisions Log

Every significant decision gets logged here. This prevents relitigating the same conversation twice.

| Decision | Rationale |
|----------|-----------|
| [What was decided] | [Why — include the reasoning, not just the outcome] |
| [What was decided] | [Why] |

---

## File Structure

```
project-name/
+-- CLAUDE.md                <- this file
+-- [main file]              <- describe what it is and its current status
+-- [supporting file]        <- describe it
+-- [folder/]
    +-- [file]               <- describe it
```

---

## What's Next

Keep this list current. At the start of each session, tell Claude to read this file and start with item 1.

1. [Highest priority — be specific enough that Claude knows exactly what to do]
2. [Next]
3. [Later]

---

## Notes for First-Time Users

- Be as specific as possible in your Hard Rules — vague rules get vague results
- Log every decision as you make it, not at the end of the session
- If Claude produces something that violates a rule, don't just accept it — correct it and consider adding a more explicit rule
- The more sessions you have, the more valuable this file becomes
- You are the creative director — this file is your brief
