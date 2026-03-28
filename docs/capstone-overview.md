# Capstone Project — Start Here

## You've Earned This

Session 00: you built a number guessing game using concepts you couldn't name yet.
Session 07: you designed your first class — your own structure, your own rules.
Session 13: you wrote a specification that two developers could implement identically.
Session 14: your app remembered things. It had persistence. It felt real.

Fifteen sessions. Fourteen projects. You learned four concepts and used them to build things that actually work.

Now the prescribed projects end. This one is yours.

---

## What This Is

This is your capstone project. You choose what to build. You choose the language, framework, and platform. You assemble your own AI development stack. You ship something you're proud of.

There are no worksheets to fill in. Instead, four Claude Code skills guide you through a professional development pipeline — from brainstorming to demo. The pipeline generates everything else specific to your project.

## How It Works

### The Pipeline

```
1. KICKOFF     → Brainstorm your project idea, define MVP, pick your tools
2. EXPLORE     → Validate your features and stack
3. LEARN       → Build your PRD, plan implementation
4. BUILD       → Implement in vertical slices with sprint checkpoints
5. MODIFY      → Add stretch features, polish for demo
6. REFLECT     → Review your process, write your report
7. DEMO        → Show what you built
```

### The Skills

Four capstone-specific skills guide you through the pipeline:

| Skill | What It Does | When to Use |
|-------|-------------|-------------|
| `capstone-kickoff` | Brainstorms your project, defines MVP, picks your toolchain | Start here |
| `capstone-stage-gen` | Generates all four stage guides for your project | Runs automatically after kickoff; run again to regenerate all |
| `capstone-sprint-check` | Demo + test + update docs + plan next slice | After each milestone |
| `capstone-critique` | AI evaluation of your final deliverables across 7 dimensions | When you're done |

Individual stage guides can be regenerated independently when your project evolves:
- "Regenerate my explore guide" — after discovering stack issues
- "Regenerate my learn guide" — after PRD changes
- "Regenerate my modify guide" — after MVP ships
- "Regenerate my reflect guide" — before demo prep

Critique dimensions can also be run individually:
- "Critique my PRD" — specification quality only
- "Critique my process" — decision log and pipeline
- "Critique my code" — implementation coverage
- "Critique my reflection" — AI harnessing and report depth

### The Ecosystems

You don't build everything from scratch. You compose your development stack from existing AI skill ecosystems.

**Superpowers** (already installed) — process discipline. Brainstorming, planning, TDD, debugging, code review. Triggers automatically.

**Everything else: search first.**

Your AI's training data has a cutoff date. Any specific ecosystem, install command, or tool it recommends from memory may be outdated, renamed, or superseded. During kickoff, the `capstone-kickoff` skill will search for the latest and most relevant ecosystems for your specific stack and domain — and show you what it found and when.

This is intentional. Learning to verify AI recommendations against live sources is part of what this capstone teaches.

**What to look for (ask your AI to search for these):**
- Claude Code skill ecosystems for your stack (e.g. "best Claude Code skills React 2026")
- Community skills for your domain (e.g. "Claude skills game dev site:github.com")
- Any domain-specific skill registries that have emerged since training cutoff

**Known starting points** (verify these are still current before using):
- `github.com/obra/superpowers` — already installed
- `github.com/garrytan/gstack` — web/full-stack
- `github.com/NousResearch/hermes-agent` — persistent AI assistants
- Search "claude code skills" on GitHub for community contributions

The kickoff skill will surface what's active and maintained for your project type.

### Your Custom Skills

For anything the ecosystems don't cover, you create your own domain-specific skills in the `skills/` directory. Examples:
- Building a game? Create a sprite generator or level design skill
- Building a dashboard? Create a chart builder or data pipeline skill
- Building a mobile app? Create a platform-specific UI patterns skill

Use Superpowers `writing-skills` to create custom skills.

## Getting Started

**Step 1:** Say "Help me brainstorm my capstone project"

That's it. The `capstone-kickoff` skill takes over from there. It'll ask you questions — one at a time. Be honest about what interests you, what you know, and what you want to learn. The more honest you are, the better the pipeline it builds for you.

**Step 2:** Follow the pipeline. Your stage guides will be generated for your specific project, stack, and goals.

---

> Build something great. Or build something just for you. Both are exactly right.

---

## What You'll Produce

By the end, you'll have:
- `planning/project-brief.md` — your decisions and vision
- `planning/prd-index.md` + `planning/prd/*.md` — your executable specification, decomposed by feature
- `planning/implementation-plan.md` + `planning/slices/*.md` — your build plan, decomposed into task cards
- `planning/decision-log.md` — your learning journey
- `planning/stages/` — your project-specific stage guides
- `src/` — working software you can demo
- A written report — your process reflection
- `skills/` — custom tools you built for your domain

Every planning document is small and self-contained — any AI model can work with any piece, and updates are surgical (change one feature's spec, not a monolithic file).

## Reference Materials

These companion docs are available alongside this file:
- [Decision Frameworks](decision-frameworks.md) — Decision-making frameworks (SWOT, MoSCoW, RICE, etc.)
- [Spec Quality](spec-quality.md) — What makes a spec vague vs executable
- [Sample PRD](sample-prd.md) — Example of a complete PRD (Habit Tracker)
