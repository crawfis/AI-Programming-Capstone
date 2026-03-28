# Capstone Project

This is a student capstone project for the Concept-First Programming Bootcamp
(AI-Based Intro to Programming, Session 15).

## Pipeline

The student drives a 7-stage pipeline: KICKOFF → EXPLORE → LEARN → BUILD → MODIFY → REFLECT → DEMO

Capstone skills guide each stage. Superpowers skills handle process discipline
(brainstorming, planning, TDD, debugging, code review).

## Artifact Locations

- `planning/project-brief.md` — vision, stack, MVP scope, toolchain
- `planning/prd-index.md` + `planning/prd/*.md` — feature specs (one file per feature)
- `planning/implementation-plan.md` + `planning/slices/*.md` — task cards (one per slice)
- `planning/decision-log.md` — append-only decision history
- `planning/stages/*.md` — generated stage guides
- `skills/` — student-created domain-specific skills
- `src/` — implementation code
- `docs/` — course reference materials (read-only)

## Working With This Project

- All planning documents are small and self-contained by design. Read only what's relevant.
- When updating planning docs, update the specific file — not a monolithic document.
- After any significant change, append to `planning/decision-log.md`.
- If scope or stack changes, regenerate stage guides via `capstone-stage-gen`.
- The student chooses their own language, framework, and platform. Do not assume a stack.
- Docs in `docs/` are course reference materials — do not modify them.

## Key Skills

- `capstone-kickoff` — brainstorm project, define MVP, select toolchain
- `capstone-stage-gen` — generate/regenerate project-specific stage guides
- `capstone-sprint-check` — checkpoint: demo, test, update docs, plan next slice
- `capstone-critique` — final evaluation across 7 dimensions
