# Backend Page Checklist

## Common Backend Page Types

| Page Type | Must Clarify |
|---|---|
| List page | filters, columns, status tags, pagination, row actions, batch actions |
| Detail page | key info, related records, operation history, editable fields |
| Form page | fields, validation, defaults, submission result, draft/cancel behavior |
| Configuration page | config item, effective scope, effective time, rollback, operator |
| Review page | queue, status, reviewer action, reject reason, history |
| Log page | object, action, operator, time, before/after, result |
| Import/export | template, file validation, permission, result report, failure handling |

## Field Checklist

| Field | Meaning |
|---|---|
| display name | what operators see |
| source | where the data comes from |
| type | text, number, enum, time, file, relation |
| required | whether empty is allowed |
| rule | validation, display, calculation, fallback |
| permission | who can view or edit |

## State Checklist

- normal
- empty
- loading
- failed
- no permission
- disabled action
- submitted/saved
- partially successful
- conflict or expired

## Permission Checklist

Clarify separately:

1. page access
2. operation access
3. data scope
4. sensitive field visibility
5. export/import access
6. log visibility

## Operation Log Checklist

For important operations, record:

- operator
- action
- object
- time
- before and after value when relevant
- result
- failure reason when relevant
