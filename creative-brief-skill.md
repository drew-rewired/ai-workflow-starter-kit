<!--
HOW TO INSTALL THIS SKILL
─────────────────────────
1. Find or create this folder on your machine: ~/.claude/skills/
   (On Mac: /Users/yourname/.claude/skills/ — create it if it doesn't exist)

2. Copy this file into that folder and rename it: creative-brief.md

3. Restart Claude Code or open a new session.

4. Type /creative-brief in any project to run it.

That's it. Nothing else to configure. Nothing to replace.
The questions below are the skill — they work as-is for any project.
-->

---
name: creative-brief
description: Run a structured creative brief before any build session. Asks focused questions to capture intent, constraints, and non-negotiables — so Claude builds what you actually mean, not what it assumes.
---

Before we write a single line of code, I want to make sure I fully understand what we're building and why.

I'm going to ask you five questions. Answer each one with as much or as little detail as you want. If something doesn't apply, say "skip" and we'll move on.

---

**1. What are we building today?**
One sentence. What is the specific screen, feature, section, or component we're working on right now?

---

**2. What is the goal of this thing?**
Not what it is — what it's *for*. What should a user feel, understand, or do when they see it? What problem does it solve?

---

**3. What must it absolutely NOT look like or behave like?**
Name a reference — an app, a style, a pattern, a word — that you want to avoid. This is as important as knowing what you want.

---

**4. What are the hard constraints?**
Anything I cannot change, override, or "improve." Specific colors. Existing components I must not touch. Interactions that are already decided. Layout rules that are locked in.

---

**5. What's the one detail that separates "close enough" from "yes, that's it"?**
There's always one thing. The specific thing that makes this feel right. What is it for this particular piece?

---

Once you've answered, I'll feed your answers back to you in my own words before building anything. If my understanding is off, correct me before I start — not after.

If at any point during the build I'm about to make a judgment call you haven't covered, I'll ask rather than assume.
