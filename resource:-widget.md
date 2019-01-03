## Name

`servicenow_widget`

## Arguments

* `identifier` - (Required) Custom Widget ID (not the internal unique identifier).
* `name` - (Required) Name of the Widget.
* `template` - (Required) HTML template of the Widget.
* `description` - (Optional) Description of the Widget.
* `css` - (Optional) Style Sheet inlined  in the Widget.
* `public` - (Optional) Whether or not this Widget is public. Default: `false`.
* `roles` - (Optional) Comma-separated list of security roles for this Widget.
* `link_function` - (Optional) Angular Link Javascript function.
* `client_script` - (Optional) Javascript script that will run on the client-side.
* `server_script` - (Optional) Javascript script that will run on the server-side.
* `option_schema` - (Optional) JSON schema of parameters available for the Widget.
* `has_preview` - (Optional) Whether or not this Widget can be previewed. Default: `false`.
* `controller_as` - (Optional) The variable name of the Angular controller in the scripts. Default: `c`.
* `demo_data` - (Optional) 
* `data_table` - (Optional)
* `protection_policy` - (Optional) Determines the resource is protected when downloaded or installed. Can be empty (`""`) for no protection, `read` for read-only protection or `protected`. Default: `read`.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.