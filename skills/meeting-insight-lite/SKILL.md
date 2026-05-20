---
name: meeting-insight-lite
description: Lightweight meeting insight skill. Use when reviewing meeting notes, transcripts, stakeholder feedback, review comments, or discussion records to extract observable concerns, decisions, action items, communication preferences, reporting needs, and follow-up wording. Focus on work signals, not private psychology.
---

# Meeting Insight Lite

## Purpose

Turn meeting material into practical collaboration signals: what people care about, what was decided, what is still unclear, what should be done next, and how to follow up.

## Load Order

1. Read `references/meeting-analysis-checklist.md`.
2. Read `references/follow-up-templates.md` when drafting messages or meeting summaries.

## Core Rule

Analyze observable behavior and stated content only. Do not diagnose personality, infer private motives, or turn one meeting into a fixed label.

## Workflow

1. Identify material type:
   - meeting notes
   - transcript
   - review comments
   - chat feedback
   - mixed discussion records
2. Extract:
   - decisions
   - open questions
   - action items
   - owner and deadline when stated
   - repeated concerns
   - evidence requested
   - risk or scope signals
3. Infer only practical work patterns:
   - prefers conclusion first or background first
   - asks for data, examples, timeline, risk, or owner
   - focuses on current result, user path, execution, quality, or scope
4. Convert into:
   - preparation advice
   - reporting order
   - follow-up message
   - next action checklist

## Output Shape

```markdown
## Meeting Summary

## Decisions

## Action Items

| Item | Owner | Deadline | Acceptance |
|---|---|---|---|

## Main Concerns

## Communication Notes

## Follow-Up Message

## Open Questions
```

## Guardrails

- Do not use insulting or clinical labels.
- Do not claim a hidden intention as fact.
- Do not assume speaker identity when names or aliases are unclear.
- Mark unsupported conclusions as assumptions.
- If a topic requires legal, finance, security, or domain review, mark it as needing specialist confirmation.
