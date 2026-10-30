---
specification_version: 0.1.0
view: notes
label: Notes
description: Every note by title.
query:
  specification_version: 0.1.0
  note_types: [note]
  select:
    - {kind: field, field: title, as: title}
    - {kind: path, as: path}
  order_by:
    - {column: title, direction: asc}
presentation:
  layout: table
  fields:
    - {column: title, label: Title}
    - {column: path, label: Path}
---

A saved view that `bun src/cli.ts view <collection> notes` prints.
