# Flow Tasks

> **Template**: `@cassems-hub-pagamento-frontend/tasks_template/tasks-template.md`

## Purpose

Break the technical plan into specific, dependency-aware tasks organized by
phase, user story, and parallelization opportunities.

## Rules

1. Each task must be actionable without excessive implicit context.
2. Preserve the independent value of user stories whenever possible.
3. Avoid vague or generic tasks.

## Required behavior

1. Read `SPEC.md`, `PLAN.md`, and available supporting artifacts (`RESEARCH.md`, `DATA_MODEL.md`, contract artifacts).
2. Generate `TASKS.md` using `@cassems-hub-pagamento-frontend/tasks_template/tasks-template.md` with Obsidian-friendly formatting, organized by:
   - phase
   - user story
   - dependencies
   - parallelizable tasks marked `[P]`
3. Highlight independent validation criteria per story when applicable.
4. Include validation steps and checkpoints when they improve execution control.
5. Include `[[INDEX]]` and links to `[[SPEC]]`, `[[PLAN]]`, `[[RESEARCH]]`,
   `[[DATA_MODEL]]`, `[[CONTRACTS]]`.
6. Update `INDEX.md`  to `tasks-ready`.

## Artifacts produced

- `TASKS.md`
- `INDEX.md` updated with `current_phase: tasks-ready`

## Final response contract

Return a visible result block in pt-BR containing:

- task count
- major phases
- current phase
