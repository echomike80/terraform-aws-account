# AWS account Terraform module

Terraform module which creates IAM roles and policies on AWS.

## Terraform versions

Terraform 0.12 and newer. 

## Usage

```hcl
module "account" {
  source    = "../../../terraform-aws-account"
  name      = var.name
}
```

## Requirements

| Name | Version |
|------|---------|
| terraform | >= 0.12.6 |
| aws | >= 2.65 |

## Providers

| Name | Version |
|------|---------|
| aws | >= 2.65 |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| name | Name to be used on all the resources as identifier | `string` | n/a | yes |

## Outputs

No output.

## Authors

Module managed by [Marcel Emmert](https://github.com/echomike80).

## License

Apache 2 Licensed. See LICENSE for full details.
