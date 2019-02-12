## Name

`servicenow_system_property_relation`

Used to create a relationship between a system_property and a system_property_category.

## Arguments

* `category_id` - (Required) System Property Category ID to link.
* `property_id` - (Required) The ID of the System Property to link.
* `order` - (Optional) The display order in the system property category's configuration page.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.