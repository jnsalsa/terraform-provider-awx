---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "awx_workflow_job_template_node_link Resource - terraform-provider-awx"
subcategory: ""
description: |-
  This resource allows you to associate and disassociate a workflow node to another one.
---

# awx_workflow_job_template_node_link (Resource)

This resource allows you to associate and disassociate a workflow node to another one.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `next_node_id` (Number) ID of the awx_workflow_job_template_node to which the link is arriving.
- `origin_node_id` (Number) ID of the awx_workflow_job_template_node from which the link is starting.
- `type` (String) The type of the link between 'origin_node_id' and 'next_node_id'. One of "success", "failure", "always"

### Read-Only

- `id` (String) The ID of this resource.
