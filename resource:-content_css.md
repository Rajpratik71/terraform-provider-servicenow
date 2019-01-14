## Name

`servicenow_content_css`

Represents a style sheet in the content management 

## Arguments

* `name` - (Required) Display name of the style sheet.
* `type` - (Optional) The type of this content management style sheet. Can be `url` or `local`. Default: `local`.
* `url` - (Optional) Used when `type` is set to `url`. Must be an absolute URL to an external style sheet file.
* `style` - (Optional) Used when `type` is set to `local`. The raw CSS content of this style sheet.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.