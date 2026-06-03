# Flow Plan

> **Templates**: `@cassems-hub-pagamento-frontend/tasks_template/plan-template.md`, `@cassems-hub-pagamento-frontend/tasks_template/research-template.md`,  
> `@cassems-hub-pagamento-frontend/tasks_template/data-model-template.md`, `@cassems-hub-pagamento-frontend/tasks_template/contracts-template.md`

## Purpose

Transform the approved specification into an executable technical plan with
research, decisions, risks, data modeling, and contracts.

## Rules

1. Separate technical decisions from business requirements clearly.
2. Use `CONTRACTS.md` by default; promote to `contracts/` when **any** of these
   are true:
   - there are two or more distinct contract types (e.g. REST API + domain event)
   - `CONTRACTS.md` would exceed ~150 lines of substantive content
   - contracts span different systems (e.g. frontend + backend + broker)
3. The plan must be executable and oriented toward incremental implementation.


## Required behavior

1. Read `SPEC.md` as the primary source.
2. Load `obsidian-vault` and `obsidian-markdown` before writing.
3. Produce all planning artifacts in pt-BR:
   - `PLAN.md` (`@cassems-hub-pagamento-frontend/tasks_template/plan-template.md`) — technical context,
     architecture decisions, dependencies, risks and mitigations, trade-offs,
     implementation strategy
   - `RESEARCH.md` (`@cassems-hub-pagamento-frontend/tasks_template/research-template.md`) — sources consulted,
     decisions and rationale, alternatives considered, reusable patterns
   - `DATA_MODEL.md` (`@cassems-hub-pagamento-frontend/tasks_template/data-model-template.md`) — entities,
     fields, relationships, lifecycle constraints, validation implications
   - `CONTRACTS.md` or `contracts/` (`@cassems-hub-pagamento-frontend/tasks_template/contracts-template.md`) —
     contract strategy, inputs/outputs, validation rules, failure modes
4. Record decisions, trade-offs, risks, and mitigations explicitly.
5. Include `[[INDEX]]` and links to adjacent artifacts in each file.
6. Update `INDEX.md` to `planned`.

## Artifacts produced

- `PLAN.md`
- `RESEARCH.md`
- `DATA_MODEL.md`
- `CONTRACTS.md` or `contracts/`
- `INDEX.md` updated with `current_phase: planned`

## Final response contract

Return a visible result block in pt-BR containing:

- files written
- planning summary
- `CONTRACTS.md` vs `contracts/` decision and justification
- current phase
