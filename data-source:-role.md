## Name

`servicenow_role`

Retrieves a Role using it's name in ServiceNow.

## Arguments

* `name` - (Required) The complete name of the role, including the suffix and the application name in prefix.

## Other attributes

* `id` - The unique identifier in the ServiceNow instance.
* `suffix` - The unique name of the role in the application.
* `description` - A description for the role.
* `elevated_privilege` - Whether or not this role has elevated privileges. Default: `false`.
* `assignable_by` - A comma-separated list of Role IDs that can assign this role to users. Admins can always assign any roles.
* `scope`- Application ID that contains this resource.