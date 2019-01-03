## Name

`servicenow_widget_dependency_relation`

A Widget Dependency Relation is used to link a Widget Dependency resource to a Widget resource.

## Arguments

* `dependency_id` - (Required) The ID of the Widget Dependency to associate to the Widget.
* `widget_id` - (Required) The ID of the Widget.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.