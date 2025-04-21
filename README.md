# AWS VPC Infrastructure using Terraform

This project provisions a VPC infrastructure on AWS using Terraform.

## 🔧 Infrastructure Components

- VPC (Custom CIDR)
- Public Subnets (2) across AZs
- Private Subnets (2) across AZs
- Internet Gateway

## 📁 Project Structure

vpc-project/
├── modules/
│   └── vpc/
│       ├── main.tf
│       ├── variables.tf
│       ├── outputs.tf
├── main.tf
├── variables.tf
├── outputs.tf
├── provider.tf
├── terraform.tfvars
└── README.md

