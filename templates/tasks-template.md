> **Idioma**: este artefato deve ser redigido em **pt-BR**.

# Tasks: [TASK TITLE]

**Task**: `[TASK_ID]`
**Input**: [[SPEC]], [[PLAN]], [[RESEARCH]], [[DATA_MODEL]], [[CONTRACTS]] or `contracts/`

**Organization**: Tasks are grouped by phase and user story to support incremental delivery.

## Format: `[ID] [P?] [REPO] [Story] Description`

- **[REPO]**: Target repository for the task (e.g., `[backend-api]`, `[frontend-app]`)

- **[P]**: Parallelizable task
- **[Story]**: User story label like `[US1]`

## Phase 1: Setup

- [ ] T001 Create implementation scaffolding for the task
- [ ] T002 Configure required dependencies or integration points

## Phase 2: Foundations

- [ ] T003 Establish shared prerequisites needed by all stories
- [ ] T004 [P] Prepare validation, error handling, and observability baseline

## Phase 3: User Story 1 - [Title]

**Goal**: [What this story delivers]

**Independent Test**: [How this story can be validated on its own]

- [ ] T005 [P] [US1] Create or update the primary data structure for this story
- [ ] T006 [US1] Implement the core service or behavior for this story
- [ ] T007 [US1] Integrate boundary or interface changes for this story

## Phase N: Polish & Cross-Cutting Concerns

- [ ] TXXX [P] Final documentation updates
- [ ] TXXX Cross-cutting validation and cleanup

## Dependencies & Execution Order

- Setup before Foundations
- Foundations before User Stories
- User Stories may proceed in parallel when dependencies allow
- Polish after the selected stories are complete

## Navegação

- [[INDEX]]
- [[SPEC]]
- [[PLAN]]
- [[RESEARCH]]
- [[DATA_MODEL]]
- [[CONTRACTS]]
