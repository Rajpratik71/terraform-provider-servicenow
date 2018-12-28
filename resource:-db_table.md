## Name

`servicenow_db_table`

## Arguments

* `label` - (Required) The display name for this table that can be localized.
* `user_role` - (Required) Role ID required for end users to access this table.
* `access` - (Optional) Whether this Script can be accessed from only this application scope or all application scopes. Values can be `package_private` or `public`. Default: `public`.
* `read_access` - (Optional) Used when access is set to `public`. Allow other application scoped to run scripts that read data from this table. Default: `false`.
* `create_access` - (Optional) Default: `false`.
* `alter_access` - (Optional) Default: `false`.
* `delete_access` - (Optional) Default: `false`.
* `web_service_access` - (Optional) Used when access is set to `public`. Flag to determine if web service calls can be made to this table. Default: `false`.
* `configuration_access` - (Optional) Used when access is set to `public`. Allow design time configuration of this table from other application scopes. Default: `false`.
* `extendable` - (Optional) Allow other tables to extend this table. Default: `false`.
* `live_feed` - (Optional) Flag to determine if live feed should be enabled for this table. Default: `false`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.
* `name` - The internal name of the table.