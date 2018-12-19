## Name

`servicenow_application`

## Arguments

* `name` - (Required) The name of the Application to retrieve from the ServiceNow instance.
* `scope` - The unique scope of the application. Normally in the format x_[companyCode]_[shortAppId]. Cannot be changed once the application is created.
* `version` - (Optional) Current version of the application. Default: `1.0.0`.

## Other attributes

* `id` - The unique identifier in the ServiceNow instance.