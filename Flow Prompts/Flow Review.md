# Flow Review

> **Template**: `.@cassems-hub-pagamento-frontend/tasks_template/code-review-template.md`

## Purpose

Record the final post-implementation code review and decide whether the task
is ready for a later transition to `done`.

## Rules

1. Require and read `REVIEW.md` as the pre-implementation readiness baseline.
2. Never mark the task `done` in this invocation — even with explicit user
   confirmation.
3. This command must always end with `current_phase: reviewed`.
4. Never auto-trigger any transition to `done`.

## Required behavior

1. Read `REVIEW.md`, `TASKS.md`, `SOLUTION.md`, and relevant repository changes.
2. Load `obsidian-vault` and `obsidian-markdown` before writing.
3. Produce `CODE_REVIEW.md` using `.@cassems-hub-pagamento-frontend/tasks_template/code-review-template.md`, focusing on: bugs and regressions, correctness, test coverage, maintainability, and closure readiness.
4. Include `[[INDEX]]`, `[[REVIEW]]`, and `[[SOLUTION]]`.
5. Update `INDEX.md` to `reviewed`.

## Artifacts produced

- `CODE_REVIEW.md`
- `INDEX.md` updated with `current_phase: reviewed`

## Gate

**Mandatory** before marking the task `done`. Explicit human confirmation
required.

## Final response contract

Return a visible result block in pt-BR containing:

- review verdict
- findings summary
- current phase
- explicit confirmation question before marking the task `done`
