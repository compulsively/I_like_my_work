---
name: document-output-lite
description: Lightweight document output skill. Use when creating or improving PRDs, requirement notes, feature specs, functional descriptions, acceptance criteria, development handoff notes, or review-ready product documents. Adjust output size by project difficulty.
---

# Document Output Lite

## Purpose

Produce the smallest useful product document for the current task: light note, standard requirement document, or complex requirement package.

## Load Order

1. Read `references/document-scale-rules.md` to choose output size.
2. Read `references/document-template.md` before producing the document.
3. If the request is still unclear, use requirement intake first.

## Workflow

1. Confirm document purpose and target reader.
2. Choose size: light, standard, or complex.
3. Separate confirmed facts from assumptions and open questions.
4. Write around user scenario, flow, rules, fields, exceptions, and acceptance.
5. Keep scope and non-scope visible.
6. Add risks and open questions when facts are missing.

## Output Rules

- Use the user's language.
- Do not over-template small tasks.
- Do not turn a document into only a page description.
- Acceptance criteria must be testable.
- If a rule, data source, metric, or owner is unknown, mark it as open instead of inventing it.

## Default Output Shape

```markdown
## Background

## Goal

## Scope

## Users And Scenarios

## Flow

## Requirements

## Rules, Fields, And States

## Exceptions

## Acceptance Criteria

## Risks And Open Questions
```
