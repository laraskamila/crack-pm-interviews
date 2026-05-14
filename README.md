# crack-pm-interviews

A Claude Code skill that tutors you through PM interview preparation, based on *Cracking the PM Interview* by McDowell & Bavaro.

## What it does

- Teaches all 11 PM interview modules (PM role, behavioral, estimation, product design, metrics, and more)
- Tracks your progress across sessions via a learner log
- Runs Socratic checks and practice scenarios inline — no separate tool needed
- Adapts to your target companies — share which companies you're interviewing at, and it focuses accordingly

## Install

```bash
/install-skill https://github.com/laraskamila/crack-pm-interviews
```

Or manually: clone this repo and add the `crack-pm-interviews/` folder to your Claude Code skills directory.

## Usage

Start a session in Claude Code:

```
let's begin interview learning
```

or

```
I want to study estimation questions
```

Claude will load your learner log (or create one on first run), orient to where you left off, and begin teaching.

## Curriculum

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

## Target Company Support

At the start of your first session, share the companies you're targeting. The skill will apply the Company Research Framework to those companies and help you build tailored rubrics for each interview.

## Learner Log

Progress is saved to `~/crack-pm-interviews/learner-progress.json` by default. You can specify a different path in SKILL.md.

## License

MIT
