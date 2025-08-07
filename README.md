# Task 3: Provision Docker Container using Terraform

## 📌 Objective
Provision a local Nginx Docker container using Terraform and the Docker provider.

## 🛠 Tools Used
- **Terraform** (Infrastructure as Code tool)
- **Docker** (Container runtime)

## 📁 Files Included
- `main.tf` – Terraform configuration file
- `README.md` – This documentation

## 📝 Steps Followed
1. Created `main.tf` using Docker provider and Nginx image
2. Ran `terraform init` to initialize the project
3. Validated using `terraform validate`
4. Planned changes using `terraform plan`
5. Applied the configuration using `terraform apply`
6. Accessed Nginx in the browser at `http://localhost:8081`
7. Listed resources using `terraform state list`
8. Destroyed infra using `terraform destroy`

## 🌐 Access
After `terraform apply`, visit:  
**http://localhost:8081**

## 🧹 Cleanup
To destroy container and image:
```bash
terraform destroy

