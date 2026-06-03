# Flow Implement

> **Template**: `@cassems-hub-pagamento-frontend/tasks_template/solution-template.md`

## Purpose

Execute the approved implementation in the target repository using vault
artifacts as the source of truth for process and intent.

## Rules

1. Do not start without a human-approved `REVIEW.md`.
2. If blocking findings exist in `REVIEW.md`, stop and request adjustments
   before implementing.
3. Use `SPEC.md`, `PLAN.md`, and `TASKS.md` as the execution baseline.

## Required behavior

1. Verify `REVIEW.md` exists and was approved.
2. Read approved vault artifacts: `SPEC.md`, `PLAN.md`, `TASKS.md`, `REVIEW.md`.
4. Update progress in `TASKS.md` as work advances.
5. Update `INDEX.md` to `implementing` at the start.
6. Produce `SOLUTION.md` using `@cassems-hub-pagamento-frontend/tasks_template/solution-template.md` when
   implementation completes, including: implemented approach, repository changes,
   validations performed, residual risks, and follow-up items.
7. Update `INDEX.md` /to `implemented` when complete,
   always refreshing `updated_at`.

## Artifacts produced

- Code and tests in the target repository
- `TASKS.md` updated
- `SOLUTION.md`
- `INDEX.md`: `implementing` during, `implemented` when done

## Final response contract

Return a visible result block in pt-BR containing:

- repository changes summary
- task progress summary
- files written
- current phase
