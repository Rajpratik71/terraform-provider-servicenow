## Name

`servicenow_role`

## Arguments

* `suffix` - (Required) The unique name of the role in the application.
* `description` - (Optional) A description for the role.
* `elevated_privilege` - (Optional) Whether or not this role has elevated privileges. Default: `false`.
* `assignable_by` - (Optional) A comma-separated list of Role IDs that can assign this role to users. Admins can always assign any roles.
* `protection_policy` - (Optional) Determines the resource is protected when downloaded or installed. Can be empty (`""`) for no protection, `read` for read-only protection or `protected`. Default: `read`.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.
* `name` - The complete name of the role, including the suffix and the application name in prefix.