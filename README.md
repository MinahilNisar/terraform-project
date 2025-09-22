# Terraform Project

This project creates a basic AWS infrastructure using Terraform:

- A VPC
- A Public Subnet
- An EC2 instance (Ubuntu Free Tier)

## Usage
- Run `terraform init` to initialize.
- Run `terraform plan` to preview.
- Run `terraform apply` to create resources.
- Use SSH to connect:  
  ```bash
  ssh -i "terra-keypair.pem" ubuntu@54.159.111.118

