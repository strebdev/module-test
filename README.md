<!-- BEGIN_TF_DOCS -->

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | n/a |
## Modules

No modules.
## Resources

| Name | Type |
|------|------|
| [aws_ssoadmin_account_assignment.ssoadmin_account_assignment](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssoadmin_account_assignment) | resource |
| [aws_ssoadmin_managed_policy_attachment.ssoadmin_managed_policy_attachment](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssoadmin_managed_policy_attachment) | resource |
| [aws_ssoadmin_permission_set.ssoadmin_permission_set](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssoadmin_permission_set) | resource |
| [aws_ssoadmin_permission_set_inline_policy.ssoadmin_permission_set_inline_policy](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssoadmin_permission_set_inline_policy) | resource |
| [aws_identitystore_group.identitystore_group](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/identitystore_group) | data source |
| [aws_ssoadmin_instances.ssoadmin_instances](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/ssoadmin_instances) | data source |
# Examples
Basic Usage:
```hcl
module "example" {
	 source  = "<module-path>"

	 # Required variables
	 aws_identitystore_group  =
	 aws_ssoadmin_account_assignment  =
	 description  =
	 iam_policy_type  =
	 name  =

	 # Optional variables
	 aws_ssoadmin_managed_policy_attachment  = {}
	 aws_ssoadmin_permission_set_inline_policy  = {}
	 session_duration  = "PT4H"
}
