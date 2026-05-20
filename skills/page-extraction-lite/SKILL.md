---
name: page-extraction-lite
description: Lightweight page extraction skill. Use when extracting structured page documentation from screenshots, product pages, screen recordings, route notes, or flow descriptions. It captures visual elements, page purpose, fields, actions, states, and flow relationships for review or RAG-ready documentation.
---

# Page Extraction Lite

## Purpose

Convert visual or descriptive page material into structured page documentation that can be reviewed, searched, or reused for requirements and prototypes.

## Load Order

1. Read `references/page-doc-template.md`.
2. Read `references/page-flow-checklist.md` when multiple pages or states are involved.

## Workflow

1. Identify page identity: name, terminal, route, source, and role.
2. Extract visible elements: navigation, sections, fields, actions, status, messages.
3. Describe interactions and state changes.
4. Capture data and business rules only when visible or provided.
5. Link pages into a flow when multiple pages exist.
6. Mark uncertain items as assumptions or unknown.

## Output Rules

- Separate visible evidence from inferred behavior.
- Do not invent hidden backend logic.
- Use stable headings and tables for searchability.
- Keep screenshots or source labels generic unless the user asks for detailed traceability.

## Default Output Shape

```markdown
# Page: [Name]

## Page Identity

## Visible Elements

## Fields And Data

## Actions

## States

## Interaction Flow

## Inferred Rules

## Unknowns
```
