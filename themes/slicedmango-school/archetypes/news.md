+++
[[fields]]
type = "text"
label = "Title"
name = "title"
[config]
required = true

[[fields]]
type = "datetime"
label = "Date"
name = "date"

[[fields]]
type = "text"
label = "Keywords"
name = "keywords"

[[fields]]
type = "textarea"
label = "Description"
name = "description"

[[fields]]
type = "field_group_list"
name = "items"
label = "Items"
[[fields]]
type = "text"
label = "News Text"
name = "news_text"
[[fields]]
type = "text"
label = "News Link"
name = "news_link"


title =  "{{ replace .TranslationBaseName "-" " " | title }}"
date = {{ .Date }}
+++
