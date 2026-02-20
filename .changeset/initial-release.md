---
"@aliou/pi-excel": minor
---

Initial release. Five tools for working with Excel files (`.xlsx`):

- `excel_describe` — inspect workbook structure: sheets, columns, row counts, and sample data.
- `excel_read` — read rows as JSON with optional sheet, row range, and column filters.
- `excel_write` — update specific cells in an existing sheet by row and column.
- `excel_add_rows` — append rows to an existing sheet by column name.
- `excel_create` — create a new workbook with one or more sheets and defined columns.

Tool execute functions are also exported via `@aliou/pi-excel/tools` for use without the pi runtime.
