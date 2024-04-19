---

database-plugin: basic

---

```yaml:dbfolder
name: HiseSnippetDB
description: Database of HiseSnippets used for the documentation of quick examples
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 1
    isHidden: false
    sortIndex: 2
    width: -194
    isSorted: true
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  category:
    input: text
    accessorKey: category
    key: category
    id: category
    label: category
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: 1
    isSorted: true
    isSortedDesc: false
    width: 145
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  author:
    input: text
    accessorKey: author
    key: author
    id: author
    label: author
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 131
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  HiseSnippet:
    input: text
    accessorKey: HiseSnippet
    key: HiseSnippet
    id: HiseSnippet
    label: HiseSnippet
    position: 5
    skipPersist: false
    isHidden: true
    sortIndex: -1
    width: 131
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  active:
    input: checkbox
    accessorKey: active
    key: active
    id: active
    label: active
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: -117
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  tags:
    input: text
    accessorKey: tags
    key: tags
    id: tags
    label: tags
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  priority:
    input: number
    accessorKey: priority
    key: priority
    id: priority
    label: priority
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: -40
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: false
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: false
  source_data: current_folder
  source_form_result: 
  source_destination_path: /
  row_templates_folder: /
  current_row_template: 
  pagination_size: 200
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```