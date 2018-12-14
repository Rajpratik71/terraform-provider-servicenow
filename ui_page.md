## Name

`servicenow_ui_page`

## Arguments

* `name` - (Required) The name of the page in ServiceNow.
* `client_script` - (Required) The Javascript script that will be added to the page client-side.
* `processing_script` - (Required) The Javascript script that will run server-side when the page is loaded.
* `html` - (Required) The HTML template of the page.
* `description` - (Optional)
* `direct` - (Optional) Whether or not to omit standard HTML header and Javascript. Default: `false`
* `category` - (Optional) The category of this page. Default: `general`

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.