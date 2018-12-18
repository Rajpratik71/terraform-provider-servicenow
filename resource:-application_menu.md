## Name

`servicenow_application_menu`

An application Menu is a section in the application navigator which includes a group of application modules.

## Arguments

* `title` - (Required) Name appearing in the menu (translated).
* `description` - (Optional) Used to provide a more detailed explanation of what this application does.
* `hint` - (Optional) Defines the text that appears in a tooltip when a user points to a link to this application.
* `device_type` - (Optional) Type of device where this menu will appear. Can be `browser` or `mobile`. Default: `browser`.
* `order` - (Optional) The display order for the application menu. Default: `100`.
* `roles` - (Optional) Comma-separated list of Roles (names) that can view this application.
* `category` - (Optional) Specifies the menu category ID, which defines the navigation menu style. The default value is Custom Applications when empty.
* `active` - (Optional) Whether or not this application is in use.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.