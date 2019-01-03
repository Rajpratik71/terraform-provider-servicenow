## Name

`servicenow_widget_dependency`

A Widget Dependency is used by Widgets to add JS and CSS includes.

## Arguments

* `name` - (Required) The display name of the Widget Dependency.
* `module` - (Optional) The Angular module name.
* `page_load` - (Optional) Whether or not to load the dependency on page load. Default: `false`.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.