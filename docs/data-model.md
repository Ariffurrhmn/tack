# Data Model

Outline of the entities Tack will store in its SQLite file. Everything here is TBD; field names and types are placeholders to be settled during implementation.

## Note

| Field | Notes |
| --- | --- |
| id | TBD |
| window kind | TBD, see Window kind |
| content | TBD |
| position | TBD |
| size | TBD |
| style | TBD, see Style |
| visibility (shown / hidden) | TBD |

## Window kind

| Field | Notes |
| --- | --- |
| kind | TBD (text, Markdown file, image, GIF, sticker) |
| source path or data | TBD |

## Style

| Field | Notes |
| --- | --- |
| color | TBD |
| font | TBD |
| font size | TBD |

## Reminder / alarm

| Field | Notes |
| --- | --- |
| note | TBD |
| hide until | TBD |
| recurrence | TBD |
| alarm | TBD |

## Attachment target

| Field | Notes |
| --- | --- |
| note | TBD |
| target type (application, site, document, folder) | TBD |
| target identifier | TBD |
