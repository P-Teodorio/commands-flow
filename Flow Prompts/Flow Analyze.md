# Flow Analyze

> **Template**: `@cassems-hub-pagamento-frontend/tasks_template/review-template.md`

## Purpose

Validate coherence across process artifacts before implementation begins and
produce a formal readiness review.

## Rules

1. Remain read-only with respect to all artifacts except `REVIEW.md`.
2. Separate critical findings from recommendations clearly.

## Required behavior

1. Read `SPEC.md`, `PLAN.md`, and `TASKS.md`.
2. Identify:
   - requirements without task coverage
   - tasks without clear justification in the spec or plan
   - terminology drift across artifacts
   - sequencing conflicts
   - non-functional gaps
3. Generate `REVIEW.md` using `@cassems-hub-pagamento-frontend/tasks_template/review-template.md`.
4. Include `[[INDEX]]` and links to `[[SPEC]]`, `[[PLAN]]`, `[[TASKS]]`.
5. Update `INDEX.md` to `analyzed`.

## Artifacts produced

- `REVIEW.md`
- `INDEX.md` updated with `current_phase: analyzed`

## Final response contract

Return a visible result block in pt-BR containing:

- review verdict
- blockers or warnings
- current phase
- explicit consent question before implementation

