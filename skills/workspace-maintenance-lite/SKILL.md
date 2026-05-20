---
name: workspace-maintenance-lite
description: Lightweight workspace maintenance skill. Use when checking folder organization, index or README drift, archive candidates, temporary files, stale notes, or whether a change should be recorded in a small history note. Always produce a confirmation checklist before moving, deleting, archiving, or rewriting shared index files.
---

# Workspace Maintenance Lite

## Purpose

Keep a working folder understandable without turning maintenance into heavy process.

## Load Order

1. Read `references/maintenance-checklist.md`.
2. Read `references/history-record-template.md` when the change is large enough to record.

## Hard Boundaries

- Do not delete, move, archive, rename, or overwrite files before the user confirms the candidate list.
- Do not rewrite indexes, README files, rules, skills, or shared notes without explicit confirmation.
- Do not remove notes, decisions, meeting records, or semantic files by name alone. Mark them as review candidates.
- If evidence is missing, say it is unknown.

## Workflow

1. Clarify maintenance scope only when it is blocking.
2. Scan for drift:
   - new or moved folders
   - stale README or index entries
   - archive candidates
   - temporary or generated files
   - missing history records after major changes
3. Classify each finding:
   - keep
   - update index/README
   - archive candidate
   - cleanup candidate
   - history record needed
   - user decision needed
4. Output a confirmation checklist.
5. After confirmation, make only the approved changes.

## History Record Habit

Create a short history note for:

- rule or skill changes
- directory migration
- index maintenance
- project phase switch
- important decisions
- changes that future teammates may need to understand

Do not create history records for every tiny edit.

## Output Shape

```markdown
## Maintenance Checklist

| Type | Item | Suggested Action | Reason | Needs Confirmation |
|---|---|---|---|---|

## History Record Needed

## Not Changing
```
