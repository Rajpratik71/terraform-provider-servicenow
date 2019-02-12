## Name

`servicenow_rest_method`

## Arguments

* `name` - (Required) A unique identifier for this HTTP method record.
* `rest_message_id` - (Required) The REST message record ID this method is based on.
* `http_method` - (Required) The HTTP method this record implements. Can be 'get', 'post', 'put', 'patch' or 'delete'.
* `rest_endpoint` - (Optional) The URL of the REST web service provider this method sends requests to. Can contain variables in the format '${variable}'.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.
* `qualified_name`