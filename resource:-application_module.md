## Name

`servicenow_application_module`

An application Module is basically a link in the application navigator.

## Arguments

* `title` - (Required) Display name of the module in the application navigator.
* `application_menu_id` - (Required) The application Menu ID where this module should reside.
* `link_type` - (Required) Type of device where this menu will appear. Can be `DIRECT` for a UI page link or `LIST` for a table link.
* `arguments` - (Required) Full name of the UI Page where this module will redirect when link type is `DIRECT`. When the link type is `LIST`, this is optional.
* `hint` - (Optional) Defines the text that appears in a tooltip when a user points to this module.
* `order` - (Optional) The display order for the module in the application menu. Default: `1`.
* `roles` - (Optional) Comma-separated list of Roles (names) that can view this application module.
* `active` - (Optional) Whether or not this application module is in enabled. Default: `true`.
* `override_menu_roles` - (Optional) Show this module when the user has the specified roles. Otherwise the user must have the roles specified by both the application menu and the module. Default: `false`.
* `window_name` - (Optional) The name of the browser window when clicking on a link. For example `_blank` can create a new tab.
* `table_name` - (Optional) The full name of the table where this module will redirect when the link type is `LIST`.
* `protection_policy` - (Optional) Determines the resource is protected when downloaded or installed. Can be empty (`""`) for no protection, `read` for read-only protection or `protected`. Default: `read`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.