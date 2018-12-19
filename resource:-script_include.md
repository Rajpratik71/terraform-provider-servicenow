## Name

`servicenow_script_include`

## Arguments

* `name` - (Required) Display name of the script. Needed to have an api_name.
* `script` - (Required) The Javascript script to run when this Script Include is called.
* `description` - (Optional) Describe what the script does.
* `client_callable` - (Optional) Whether or not this script can be called from the client-side or only server-side. Default: `false`.
* `active` - (Optional) Whether or not this Script Include is enabled. Default: `true`.
* `access` - (Optional) Whether this Script can be accessed from only this application scope or all application scopes. Values can be `package_private` or `public`. Default: `package_private`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.
* `api_name` - Full name of the Script Include needed to call it.