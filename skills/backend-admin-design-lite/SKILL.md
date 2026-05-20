---
name: backend-admin-design-lite
description: Lightweight backend admin design skill. Use when designing or reviewing admin console pages, management workflows, list/detail/form pages, filters, batch actions, permissions, configuration modules, operation logs, export/import rules, or backend handoff notes. Adjust output size by backend task difficulty.
---

# Backend Admin Design Lite

## Purpose

Create practical backend admin designs without requiring a full enterprise governance package. Focus on page purpose, operator workflow, data fields, actions, permissions, states, logs, and acceptance criteria.

## Load Order

1. Read `references/backend-scope-rules.md`.
2. Read `references/backend-page-checklist.md`.
3. Read `references/backend-output-template.md` before producing specs or prototype briefs.

## Workflow

1. Identify target artifact:
   - backend requirement note
   - admin page spec
   - list/detail/form design
   - configuration module
   - permission/log/export rule
   - prototype brief
2. Classify difficulty: light, standard, complex, or console-level.
3. Define operator goal and task path.
4. Specify page structure:
   - navigation and entry
   - filters/search
   - table/list/detail/form
   - actions
   - states
   - permissions
   - logs
5. Add fields, rules, exceptions, and acceptance criteria.
6. Mark unknown system behavior as open questions.

## Output Rules

- Do not assume a specific UI library.
- Do not design only a table; include operator workflow and result state.
- Do not write "controlled by permission" without specifying page, operation, data, and export permissions when relevant.
- Do not invent backend APIs, database fields, roles, or audit policies.
- Keep the output as small as the task allows.

## Output Shape

```markdown
## Backend Task Summary

## Scope

## Operator Workflow

## Page Structure

## Fields And Data

## Actions And Rules

## Permissions And Logs

## States And Exceptions

## Acceptance Criteria

## Open Questions
```
