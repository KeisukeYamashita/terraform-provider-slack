---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "slack Provider"
subcategory: ""
description: |-
  
---

# slack Provider



## Example Usage

```terraform
provider "slack" {
  token = "xoxb-xxxx-xxxx-xxxx" // Or SLACK_TOKEN enivoronment variable
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **token** (String) The OAuth token used to connect to Slack. This can also be set via the SLACK_TOKEN environment variable.
