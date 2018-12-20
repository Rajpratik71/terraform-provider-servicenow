## Name

`servicenow_ui_macro`

## Arguments

* `name` - (Required) The name of the UI Macro.
* `xml` - (Required) The body of the UI Macro. Must be in XML format.
* `api_name` - (Optional) The scoped name of the macro. Normally contains the name field prefixed with the application scope. Requires a new resource when changed.
* `description` - (Optional) A description of what the Macro does.
* `active` - (Optional) Whether or not this Macro is enabled. Default: `true`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.