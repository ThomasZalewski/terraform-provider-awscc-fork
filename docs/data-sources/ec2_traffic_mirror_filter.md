---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "awscc_ec2_traffic_mirror_filter Data Source - terraform-provider-awscc"
subcategory: ""
description: |-
  Data Source schema for AWS::EC2::TrafficMirrorFilter
---

# awscc_ec2_traffic_mirror_filter (Data Source)

Data Source schema for AWS::EC2::TrafficMirrorFilter



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `id` (String) Uniquely identifies the resource.

### Read-Only

- `description` (String) The description of a traffic mirror filter.
- `network_services` (Set of String) The network service that is associated with the traffic mirror filter.
- `tags` (Attributes List) The tags for a traffic mirror filter. (see [below for nested schema](#nestedatt--tags))
- `traffic_mirror_filter_id` (String) The ID of a traffic mirror filter.

<a id="nestedatt--tags"></a>
### Nested Schema for `tags`

Read-Only:

- `key` (String)
- `value` (String)
