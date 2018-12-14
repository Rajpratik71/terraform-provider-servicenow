Welcome to the terraform-provider-servicenow documentation!

Here you should find documentation about Resources available in this provider. Feel free to contribute, any help is appreciated.

## Example usage

Example Terraform file with the provider and a single resource:

    provider "servicenow" {
      instance_url = "${var.ServiceNowUrl}"
      username     = "${var.ServiceNowUser}"
      password     = "${var.ServiceNowPwd}"
    }

    variable "ServiceNowUrl" {}

    variable "ServiceNowUser" {}

    variable "ServiceNowPwd" {}

    resource "servicenow_ui_page" "test-page" {
      name              = "My test page"
      description       = "This is a description!"
      html              = "${file("${path.module}/test-page/test-page.html")}"
      client_script     = ""
      processing_script = "${file("${path.module}/test-page/test-page.server_script.js")}"
      category          = "general"
      direct            = false
    }

