# Flow Specify

> **Template**: `@cassems-hub-pagamento-frontend/tasks_template/spec-template.md`

## Purpose

Transform context and discovery into a formal functional specification centered
on user stories, requirements, success criteria, and edge cases.

## Rules

1. Maintain a clear distinction between business rules, hypotheses, dependencies,
   and out-of-scope items.
2. Keep the specification technology-agnostic whenever possible.

## Required behavior

1. Read `CONTEXT.md` and `DISCOVERY.md`.
2. Load `obsidian-vault` and `obsidian-markdown` before writing.
3. Generate `SPEC.md` using `@cassems-hub-pagamento-frontend/tasks_template/spec-template.md`, ensuring:
   - overview
   - user stories with acceptance criteria and independent tests
   - functional requirements labeled `FR-XXX`
   - measurable success criteria labeled `SC-XXX`
   - edge cases
   - dependencies, assumptions, and out-of-scope items
4. Include `[[INDEX]]` and links to `[[CONTEXT]]` and `[[DISCOVERY]]`.
5. Spec must remain understandable to non-technical stakeholders.
6. Do not include implementation details unless explicitly justified as a
   business constraint.
7. Update `INDEX.md` to `spec-ready`.

## Artifacts produced

- `SPEC.md`
- `INDEX.md` updated with `current_phase: spec-ready`

## Final response contract

Return a visible result block in pt-BR containing:

- files written
- current phase
- key sections produced
- gaps identified for clarification (if any)

