## Name

`servicenow_css_include`

## Arguments

* `name` - (Required)
* `source` - (Optional) The type of source where the style sheet is saved. Default: `url`. Possible values: `url`, `local`
* `url` - (Optional) Required if `source` is set to `url`. This must be an **absolute** URL to a style sheet file.
* `css_id` - (Optional) Required if `source` is set to `local`. This must be the ID of a css Style Sheet in ServiceNow.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.