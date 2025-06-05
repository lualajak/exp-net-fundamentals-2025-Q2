##VPC Settings

Below are the details for the VPC CFN Automation Creation that i observed from the tutor
- Name Tag: Exp-net-vpc
- IPV4 CIDR BLock: 10.200.123.0/24
- IPV6 CIDR Block: No
- Number of AZs: 1
- Number of Private Subnets: 1
- Number of Public Subnets: 1
- NAT Gateways: None
- VPC Endpoints: None
- DNS Options: Enable DNS Hostnames
- DNS Options: Enable DNS Resolution

## CFN Template Generation and Review
I Noted a couple of VPC Settings. Provided the Settings to ChatGPT to generate a CFN Template to automate the VPC Infrastrature

## Generated Bash Deployment Script
Using ChatGPT, i genetated bash script `bin/deploy`

## Visualization in Infrastructure Composer

Sample of Visual Representation of VPC using AWS Toolkit Infrastructure Composer

![](assets/aws_infr_composer.png)

## CLI Installation

Inorder to deploy via AWS Cli, AWS CLI must be install.
This is the the link to the cli installation guide
## https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

## Deployment
Below is resource map of the VPC Deployed using CFN
![](assets/aws_vpc_resource_map.png)
