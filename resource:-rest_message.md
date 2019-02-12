## Name

`servicenow_rest_message`

## Arguments

* `name` - (Required) Descriptive name for this REST message.
* `rest_endpoint` - (Required) The URL of the REST web service provider this REST message sends requests to.  Can contain variables in the format '${variable}'.
* `description` - (Optional) Description for this REST message.
* `access` - (Optional) Whether this REST message can be accessed from only this application scope or all application scopes. Values can be 'package_private' or 'public'.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.