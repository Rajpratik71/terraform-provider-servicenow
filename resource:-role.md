## Name

`servicenow_role`

## Arguments

* `suffix` - (Required) The unique name of the role in the application.
* `description` - (Optional) A description for the role.
* `elevated_privilege` - (Optional) Whether or not this role has elevated privileges. Default: `false`.
* `assignable_by` - (Optional) A comma-separated list of Role IDs that can assign this role to users. Admins can always assign any roles.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.
* `name` - The complete name of the role, including the suffix and the application name in prefix.