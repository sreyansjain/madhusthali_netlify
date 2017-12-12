---
hide_body: true
fields:
- type: text
  label: Title
  name: title
  config:
    required: true
- type: datetime
  name: date
  label: Date
- type: field_group_list
  name: news
  label: News
  fields:
  - type: text
    name: news_text
    label: News Text
  - type: text
    label: News Link
    name: news_link
---
