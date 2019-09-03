## Name

`servicenow_db_table`

## Arguments

* `name` - (Required) The internal name of the table.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.
* `label` - The display name for this table that can be localized.
* `user_role` - Role ID required for end users to access this table.
* `access` - Whether this Script can be accessed from only this application scope or all application scopes. Values can be `package_private` or `public`.
* `read_access` - Used when access is set to `public`. Allow other application scoped to run scripts that read data from this table.
* `create_access`
* `alter_access`
* `delete_access`
* `web_service_access` - Flag to determine if web service calls can be made to this table.
* `configuration_access` - Allow design time configuration of this table from other application scopes.
* `extendable` - Allow other tables to extend this table.
* `live_feed` - Flag to determine if live feed should be enabled for this table.
* `scope`- Application ID that contains this resource.
