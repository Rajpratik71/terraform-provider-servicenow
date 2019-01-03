## Name

`servicenow_js_include`

## Arguments

* `display_name` - (Required)
* `source` - (Optional) The type of source where the script is saved. Default: `url`. Possible values: `url`, `local`
* `url` - (Optional) Required if `source` is set to `url`. This must be an **absolute** URL to a script file.
* `ui_script_id` - (Optional) Required if `source` is set to `local`. This must be the ID of a UI Script in ServiceNow.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.