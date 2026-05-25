# Terraform AWS Infrastructure

## Overview

This project provisions AWS infrastructure using Terraform.

The infrastructure includes:

- VPC
- Public Subnet
- Internet Gateway
- Route Table
- Security Group
- EC2 Instance

---

# Architecture

User → Internet Gateway → Public Subnet → EC2 Instance

---

# Technologies Used

- Terraform
- AWS
- EC2
- VPC
- Linux

---

# Files Included

| File | Purpose |
|------|----------|
| main.tf | Main infrastructure code |
| variables.tf | Variable definitions |
| terraform.tfvars | Variable values |
| outputs.tf | Output values |
| README.md | Project documentation |

---

# Terraform Commands

## Initialize Terraform

```bash
terraform init
```

## Validate Configuration

```bash
terraform validate
```

## Preview Infrastructure

```bash
terraform plan
```

## Create Infrastructure

```bash
terraform apply
```

## Destroy Infrastructure

```bash
terraform destroy
```

---

# Features

✔ Automated Infrastructure Provisioning

✔ EC2 Instance Creation

✔ Secure VPC Networking

✔ Infrastructure as Code

✔ Reusable Terraform Templates

---

# Learning Outcomes

- Understanding Terraform workflow
- Infrastructure as Code concepts
- AWS resource provisioning
- VPC networking basics
- Security Group configuration

---


---

# Author

Sabari Dharshini
DevOps & Cloud Enthusiast
