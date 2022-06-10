## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | 4.18.0 |
| <a name="provider_null"></a> [null](#provider\_null) | 3.1.1 |

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_hosted-zone-module"></a> [hosted-zone-module](#module\_hosted-zone-module) | ./modules/ | n/a |

## Resources

| Name | Type |
|------|------|
| [aws_route53_zone_association.second-association](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route53_zone_association) | resource |
| [aws_vpc.first-vpc](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc) | resource |
| [aws_vpc.second-vpc](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc) | resource |
| [null_resource.hostedscript](https://registry.terraform.io/providers/hashicorp/null/latest/docs/resources/resource) | resource |
| [aws_route53_zone.selected](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/route53_zone) | data source |
| [aws_vpc.targetVpc_1](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/vpc) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_custom-domain-name"></a> [custom-domain-name](#input\_custom-domain-name) | n/a | `string` | n/a | yes |

## Outputs

No outputs.
