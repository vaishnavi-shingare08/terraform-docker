# 🚀 Task 3: Infrastructure as Code (IaC) with Terraform & Docker

## ✅ Objective
Provision a local Docker container (nginx) using Terraform on an AWS EC2 instance. This project demonstrates Infrastructure as Code (IaC) using Terraform to automate Docker container provisioning.

---

## 🔧 Tools Used

- Terraform v1.8.5
- Docker
- AWS EC2 (Amazon Linux / Ubuntu)
- Git & GitHub

---

## 📦 What It Does

- Initializes the Terraform Docker provider
- Pulls the latest nginx Docker image
- Creates a Docker container named nginx_container
- Exposes port 8080 on your EC2 instance (mapped to port 80 inside container)

---

## 📁 Files Included

| File          | Description                          |
|---------------|--------------------------------------|
| main.tf     | Terraform configuration file         |
| output.txt  | Terraform command logs               |
| README.md   | This documentation file              |

---

## 🚀 How to Use

### 1️⃣ Clone the repository
```bash
git clone https://github.com/vaishnavi-shingare08/terraform-docker.git
cd terraform-docker
