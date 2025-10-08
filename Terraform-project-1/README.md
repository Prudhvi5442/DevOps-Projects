# 🌩️ Setting up AWS Infrastructure using Terraform

This project demonstrates how to automate AWS infrastructure provisioning using **Terraform**.  
It creates a complete setup including a **VPC**, **2 public subnets**, an **Application Load Balancer**, **EC2 instances**, and an **S3 bucket**.

---

## 🧠 Architecture Overview

![AWS Terraform Architecture](https://github.com/Prudhvi5442/DevOps-Projects/blob/951606e84f7f88e649d97a417f68011693e34f67/Terraform-project-1/AWS%20Terraform%20Infra.jpg)

### Components:
- **VPC** 
- **2 Public Subnets** 
- **Internet Gateway & Route Table**
- **Security Group** 
- **2 EC2 Instances** 
- **Application Load Balancer (ALB)**
- **Amazon S3 Bucket**

---

## ⚙️ Workflow

1. **VPC Creation** – Defines the network environment.
2. **Subnets** – Two public subnets in different AZs for high availability.
3. **Internet Gateway & Route Table** – Enables internet access.
4. **Security Groups** – Control inbound/outbound rules.
5. **EC2 Instances** – Hosts the web servers.
6. **ALB Setup** – Distributes HTTP traffic evenly across instances.
7. **S3 Bucket** – For file or static website storage.

---


