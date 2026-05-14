# crack-pm-interviews

A skill for [Claude Code](https://claude.ai/code) that tutors you through PM interview preparation, based on *Cracking the PM Interview* by McDowell & Bavaro.

It teaches all 11 PM interview modules, tracks your progress across sessions, runs practice scenarios inline, and adapts to the specific companies you're interviewing at.

---

## Prerequisites

Before installing this skill, you need:

1. **Claude Code** — download the desktop app at [claude.ai/code](https://claude.ai/code) or install the CLI:
   ```bash
   npm install -g @anthropic-ai/claude-code
   ```

2. **Node.js** — required to run the `npx` install command. Download at [nodejs.org](https://nodejs.org) if you don't have it.

---

## Install

Run this in your terminal:

```bash
npx skills add https://github.com/laraskamila/crack-pm-interviews --skill crack-pm-interviews
```

That's it. The skill is now available in any Claude Code session.

---

## Usage

Open Claude Code and type any of the following to get started:

```
let's begin interview learning
```
```
I want to study estimation questions
```
```
teach me the STAR method
```
```
what module should I study next
```
```
help me understand product design questions
```

Claude will create a learner log on first run, then pick up from where you left off in every future session.

---

## What it covers

| Module | Topic |
|--------|-------|
| 1 | The PM Role & Mindset |
| 2 | Companies & Interview Styles |
| 3 | Define Yourself (Self-Definition Questions) |
| 4 | Behavioral Story Questions (STAR) |
| 5 | Estimation Questions |
| 6 | Product Design Questions |
| 7 | Product Improvement & Favorite Product |
| 8 | Case Questions & Business Frameworks |
| 9 | Metrics & Analytics |
| 10 | Coding Questions for PMs |
| 11 | Resume & Cover Letter Craft |

Each module includes explanations, worked examples, Socratic checks, and live practice — all within the conversation.

---

## Target company support

At the start of your first session, share the companies you're targeting. The skill will focus Module 2 on those companies and help you build a preparation rubric for each one.

```
I'm interviewing at Stripe and Figma for a PM role
```

---

## Progress tracking

Your progress is saved automatically to `~/crack-pm-interviews/learner-progress.json` after every session. When you come back, the skill reads this log and picks up where you left off — no need to repeat yourself.

To use a different save location, update the log path in `~/.claude/skills/crack-pm-interviews/SKILL.md`.

---

## Attribution & Use

The curriculum content in this skill is a teaching aid derived from *Cracking the PM Interview* by Gayle Laakmann McDowell & Jackie Bavaro (Career Cup, 2013). All frameworks, chapter references, and interview strategies are attributed to that work.

This repository contains no verbatim text from the book — only structured summaries and teaching notes. It is intended for personal, educational use to help individuals prepare for PM interviews.

**If you find this useful, please buy the book.** It is the authoritative source and worth owning:
[Cracking the PM Interview on Amazon](https://www.amazon.com/dp/0984782818)

The skill code itself (SKILL.md, learner-log-template.json, and the Claude Code scaffolding) is released under the MIT License. See [NOTICE](NOTICE) for full attribution details.
