# Maintenance Checklist

## Scan Areas

| Area | Look For |
|---|---|
| Folder structure | new folders, moved folders, unclear ownership |
| Index/README | missing new artifact, stale path, wrong description |
| Archive candidates | old version, replaced draft, deprecated skill, inactive material |
| Cleanup candidates | temp, cache, generated output, duplicate export |
| Semantic records | notes, decisions, meetings, reviews, history logs |
| History records | major change without a short rationale |

## Candidate Classification

| Classification | Meaning |
|---|---|
| keep | no change needed |
| update index | index or README should mention the new state |
| archive candidate | likely old but needs confirmation |
| cleanup candidate | likely removable generated/temp file but needs confirmation |
| history needed | create a short record of why the change happened |
| user decision | cannot judge safely |

## Confirmation Rule

Before any destructive or structural change, output:

```markdown
| Candidate | Current Location | Proposed Action | Reason |
|---|---|---|---|
```

Wait for explicit confirmation before acting.
