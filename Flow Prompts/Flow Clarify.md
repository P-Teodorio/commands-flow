# Flow Clarify

> **Template**: `@cassems-hub-pagamento-frontend/tasks_template/spec-template.md`

## Purpose

Reduce ambiguity and complete missing business rules in `SPEC.md` using the smallest reasonable number of questions.

## Rules

1. Ask only about issues that materially affect scope, acceptance criteria, UX, data semantics, or critical behavior.
2. Integrate accepted answers directly into `SPEC.md` incrementally.
3. Do not ask questions that belong to technical planning.

## Required behavior

1. Read `SPEC.md`.
2. Detect only ambiguities that materially affect scope, business behavior, user experience, data meaning, or acceptance criteria.
3. Formulate a limited number of targeted questions.
4. After accepted answers: update `SPEC.md` incrementally, preserving readability without duplicating or contradicting existing text.
5. Update `INDEX.md`  to `clarified` when the spec is ready for planning.

## Artifacts produced

- `SPEC.md` updated
- `INDEX.md` updated with `current_phase: clarified`

## Final response contract

Return a visible result block in pt-BR containing:

- ambiguities addressed
- sections updated
- current phase
