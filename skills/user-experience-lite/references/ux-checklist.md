# UX Checklist

## Core Questions

| Area | Question |
|---|---|
| User | Who is using this and in what situation? |
| Goal | What does the user want to complete? |
| Entry | Where does the user start? |
| Priority | Is the primary action obvious? |
| Flow | Can the user move from start to finish without guessing? |
| Feedback | Does every important action produce visible feedback? |
| Recovery | Can the user recover from error, empty, timeout, or no permission states? |
| Trust | Does the interface explain important rules, risks, and results? |
| Efficiency | Are repeated or high-frequency actions easy enough? |
| Accessibility | Is text, contrast, target size, and state indication usable enough? |

## Friction Types

- unclear page purpose
- hidden primary action
- too much explanation before action
- missing empty/error/loading/success state
- form field unclear or too strict
- destructive action without confirmation
- status label without next action
- user cannot tell whether the action succeeded
- backend operator must remember context manually
- content hierarchy makes scanning difficult

## Evidence Levels

| Level | Meaning |
|---|---|
| Observed | Visible in provided artifact or screenshot |
| Provided | Stated by the user or source material |
| Inferred | Reasonable deduction; needs confirmation |
| Unknown | Not available |

## Experience Acceptance Criteria Examples

- User can identify the primary action within the first screen.
- User receives clear feedback after submission.
- Empty state explains why there is no data and what to do next.
- Error state gives a recoverable next action.
- Disabled action explains why it is unavailable when relevant.
- Backend operator can complete the high-frequency task without opening unrelated pages.
