# WORKFLOW.md (Step 2)

## Role Split
- **Jeremy (Owner):** sets priority and approves direction
- **Remy (Orchestrator):** plans tasks, prepares handoff, reviews output
- **Codex (Builder):** implements code changes and tests

## Standard Flow
1. Jeremy gives priority (what to improve)
2. Remy fills `TASK_TEMPLATE.md`
3. Remy creates a build handoff in `HANDOFF.md`
4. Codex implements only scoped changes
5. Remy runs release checklist
6. Jeremy approves go-live

## Rules
- No coding without a clear scope
- No deploy without checklist pass
- Business decisions stay with Jeremy
- Code implementation stays with Codex
