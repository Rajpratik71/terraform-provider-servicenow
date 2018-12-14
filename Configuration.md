For the provider to work, you need to provider these parameters:

* `instance_url` : The URL of the ServiceNow instance.
* `username` : The username used for Basic authentication when making API calls.
* `password` : The password of the user used for authentication.

You can create Terraform variables to automatically fetch these values from environment variables or simply pass them to the provider on command line execution.