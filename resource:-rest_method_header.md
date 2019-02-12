## Name

`servicenow_rest_method_header`

## Arguments

* `name` - (Required) The name of the header to add to the HTTP request.
* `value` - (Required) The value of the header to add to the HTTP request.
* `rest_method_id` - (Required) The REST method record ID this header will be applied to.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.