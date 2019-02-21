## Name

`servicenow_ui_script`

## Arguments

* `name` - (Required) The short name of the UI Script.
* `description` - (Optional) A description of what the script does.
* `script` - (Required) The actual Javascript script.
* `type` - (Optional) The type of device this script applies to. Can be `all`, `desktop` or `mobile`. Default: `all`.
* `active` - (Optional) Whether or not this Script is enabled. Default: `true`.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.
* `api_name` - The full name of the UI Script.