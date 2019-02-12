## Name

`servicenow_system_property`

## Arguments

* `suffix` - (Required) Internal suffix for the property used to create the name.
* `type` - (Optional) Type of the property. Can be `string` or `choicelist`. Default: `string`.
* `choices` - (Optional) Comma-separated list of possible choices when the type is set to 'choicelist'. The values can be in format 'label=value' for alternate display labels.
* `is_private` - (Optional) If set to `true`, this property will not move from one site to another. Default: `false`.
* `ignore_cache` - (Optional) If set to `true`, changing this property will not flush the cache. Default: `false`.
* `description` - (Optional) Short description of the property that will be displayed above it in the UI.
* `write_roles` - (Optional) Comma-separated list of security roles required to modify this property.
* `read_roles` - (Optional) Comma-separated list of security roles required to read this property.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.
* `name` - Internal name of the property used to access it in scripts.