---
name: requirement-intake-lite
description: Lightweight requirement intake skill. Use when a request is vague, scattered, or not yet ready for document or prototype output. It clarifies goal, user, scenario, scope, constraints, missing facts, and project difficulty while asking only blocking questions.
---

# Requirement Intake Lite

## Purpose

Turn vague ideas, meeting notes, stakeholder comments, screenshots, or partial requests into a small requirement brief that can drive document or prototype work.

## Load Order

1. Read `references/intake-checklist.md`.
2. If the user already provided enough information, do not run a long questionnaire. Produce the brief directly and mark remaining assumptions.

## Workflow

1. Identify the intended next artifact:
   - requirement document
   - prototype
   - page extraction
   - audit/review
   - unclear
2. Classify difficulty: light, standard, or complex.
3. Extract the minimum usable facts:
   - problem and goal
   - user role and scenario
   - scope and non-scope
   - main flow
   - key fields/rules/states
   - constraints and risks
   - open questions
4. Ask only the questions that block the next artifact.
5. Output a short intake brief and recommended next skill.

## Output Shape

```markdown
## Intake Summary

## Project Difficulty

## Confirmed Information

## Assumptions

## Missing Blocking Questions

## Recommended Next Step
```

## Guardrails

- Do not invent business facts, metrics, dates, owners, policies, system abilities, or legal conclusions.
- Do not ask for every possible detail when a light output is enough.
- If information is missing but non-blocking, mark it as an assumption and continue.
- Keep this skill as intake only; hand off to document, prototype, page extraction, or audit skills for production.
