# cfn-vpc
Cloudformation to execute vpc stacks

# vpc-2azs.yaml
Implements the network cenario [VPC with Public and Private Subnets (NAT)](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Scenario2.html) with a /23 VPC with Internet Gateway and four /23 subnets. Two publics with NATGateway, and two routed private subnets.
It's based on templates from [Clodnaut.io](https://templates.cloudonaut.io/en/stable/vpc/).
