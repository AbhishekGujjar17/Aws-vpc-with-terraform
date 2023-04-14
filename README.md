# Aws-vpc-with-terraform
Terraform code that creates resources in aws which include a vpc, subnets, internet gateway, route tables and associations, security groups, network interfaces, elastic-ip and ec2-instance.
AWS VPC Creation with Terraform
This Terraform project creates AWS resources including a VPC, subnets, Internet Gateway, Route Tables and Associations, Security Groups, Network Interfaces, Elastic IP, and an EC2 instance.

# Prerequisites
To use this project, you will need:

An AWS account with appropriate permissions

Terraform installed on your local machine

# Installation
Clone this repository using git clone https://github.com/yourusername/aws-vpc-terraform.git

Navigate to the project directory

Run terraform init to initialize the Terraform project

Run terraform apply to create the AWS resources

# Usage
To use the created VPC and resources, you can launch an EC2 instance in one of the subnets. Make sure to assign the appropriate security group to the instance.

# Resources Created
1 VPC with CIDR block of 10.0.0.0/16

2 public subnets with CIDR blocks of 10.0.1.0/24 and 10.0.2.0/24

1 private subnet with a CIDR block of 10.0.3.0/24

1 Internet Gateway

2 Route Tables and Associations (1 public, 1 private)

2 Security Groups (1 for the EC2 instance, 1 for the VPC)

1 Network Interface

1 Elastic IP

1 EC2 instance

# Customization
You can customize the VPC and resources created by modifying the variables in the variables.tf file.

# Cleanup
To destroy the AWS resources created by this project, run terraform destroy.

# Acknowledgements
Terraform for providing a tool to automate infrastructure deployment

AWS for providing a robust cloud computing platform.
