---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "wordpress Provider"
subcategory: ""
description: |-
  
---

# wordpress Provider



## Example Usage

```terraform
provider "wordpress" {
  endpoint = "http://localhost:8000/wp-json/wp/v2"
  user = "wp"
  password = "wp"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `endpoint` (String)
- `password` (String, Sensitive)
- `user` (String)
