## Name

`servicenow_ui_macro`

## Arguments

* `name` - (Required) The name of the UI Macro.
* `xml` - (Required) The body of the UI Macro. Must be in XML format.
* `api_name` - (Optional) The scoped name of the macro. Normally contains the name field prefixed with the application scope. Requires a new resource when changed.
* `description` - (Optional) A description of what the Macro does.
* `active` - (Optional) Whether or not this Macro is enabled. Default: `true`.
* `protection_policy` - (Optional) Determines the resource is protected when downloaded or installed. Can be empty (`""`) for no protection, `read` for read-only protection or `protected`. Default: `read`.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.