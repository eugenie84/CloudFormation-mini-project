# CloudFormation-mini-project
Repository for my GIT apache-web-cfn
Overview
This project streamlines the deployment of AWS resources by providing two CloudFormation templates - one for creating a Virtual Private Cloud (VPC) and another for launching an Amazon EC2 instance within the VPC. This modular approach allows users to configure VPC settings independently of the EC2 instance, providing flexibility and customization.
- VPC Template ("Sample-VPC.yml")
The VPC template facilitates the creation of a VPC with customizable parameters such as CIDR block, subnets, and security groups. Users can define public and private subnets, configure network access controls, and tailor the VPC architecture to their specific requirements.
- EC2 Template ("Sample-EC2.yml")
Once the VPC is established using the VPC template, the EC2 template is used to launch an Amazon EC2 instance within the VPC. This template allows users to specify the instance type, key pair, and other parameters, providing granular control over the EC2 environment.
