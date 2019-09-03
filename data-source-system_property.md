## Name

`servicenow_system_property`

## Arguments

* `name` - (Required) Internal name of the property used to access it in scripts.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.
* `suffix` - Internal suffix for the property used to create the name.
* `type` - Type of the property. Can be `string` or `choicelist`.
* `choices` - Comma-separated list of possible choices when the type is set to 'choicelist'. The values can be in format 'label=value' for alternate display labels.
* `is_private` - If set to `true`, this property will not move from one site to another.
* `ignore_cache` - If set to `true`, changing this property will not flush the cache.
* `description` - Short description of the property that will be displayed above it in the UI.
* `write_roles` - Comma-separated list of security roles required to modify this property.
* `read_roles` - Comma-separated list of security roles required to read this property.
* `scope`- Application ID that contains this resource. Changes forces a new resource.
