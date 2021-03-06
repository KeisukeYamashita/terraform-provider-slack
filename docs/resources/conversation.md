---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "slack_conversation Resource - terraform-provider-slack"
subcategory: ""
description: |-
  Channel-like things encountered in Slack
---

# slack_conversation (Resource)

Channel-like things encountered in Slack

## Example Usage

```terraform
resource "slack_conversation" "conversation" {
  name    = "my-channel"
  topic   = "My personal channel"
  purpose = "Daily communication"

  is_archived = flase
  is_private  = flase

  action_on_destroy = "archive"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **action_on_destroy** (String) Either of none or archive
- **is_private** (Boolean)
- **name** (String)

### Optional

- **id** (String) The ID of this resource.
- **is_archived** (Boolean)
- **purpose** (String)
- **topic** (String)

### Read-Only

- **created** (Number)
- **creator** (String)
- **is_ext_shared** (Boolean)
- **is_org_shared** (Boolean)
- **is_shared** (Boolean)

## Import

Import is supported using the following syntax:

```shell
terraform import slack_coversation.conversation Cxxxxxxxxx
```
