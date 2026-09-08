---
specification_version: 0.1.0
note_type: note
description: A general-purpose example note.
storage:
  folder_pattern: Notes
  note_name_pattern: "{title}"
frontmatter:
  title:
    type: text
    nullable: false
    not_blank: true
  tags:
    type: tags
    nullable: false
---

The example note type demonstrates a required title and collection policy tag.
