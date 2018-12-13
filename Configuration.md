For the provider to work, you need to provider these parameters:

* `ServiceNowUrl` : The URL of the ServiceNow instance.
* `ServiceNowUser` : The username used for Basic authentication when making API calls.
* `ServiceNowPwd` : The password of the user used for authentication.

The parameters are automatically retrieved using Terraform variables, so you can add these equivalent environment variables which will be fetched on any terraform commands:

* `TF_VAR_ServiceNowUrl`
* `TF_VAR_ServiceNowUser`
* `TF_VAR_ServiceNowPwd`