
# 🚀 Provision Nginx Container using Terraform and Docker

This project provisions a local Nginx container using Terraform and Docker. It demonstrates how to automate container deployment with Infrastructure as Code (IaC) using Terraform.

---

## 📦 What I Did

✅ Installed **Terraform v1.11.4** and added it to system environment variables  
✅ Installed and started **Docker Desktop**  
✅ Created a new folder `terraform-docker-task`  
✅ Created the following Terraform files:
- `provider.tf`
- `main.tf`
- `variables.tf`
- `outputs.tf`

✅ Wrote code to:
- Pull the `nginx:latest` image from Docker Hub
- Start a Docker container mapped to local port `8080`
  
✅ Ran the following commands:
```bash
terraform init
terraform apply
✅ Opened browser and visited:
👉 http://localhost:8080
✅ Successfully saw the “Welcome to nginx!” default page 🎉

📂 Project Files
terraform-docker-task/
├── main.tf
├── provider.tf
├── variables.tf
├── outputs.tf
├── terraform.tfstate
├── .terraform/
└── screenshots/
    ├── main-tf-code.png
    ├── terraform-apply-output.png
    └── nginx-welcome-page.png
🧾 Screenshots
All screenshots are saved in the screenshots/ folder and uploaded to GitHub:

✅ main.tf Terraform code

✅ terraform apply output

✅ Nginx Welcome Page on browser

👨‍💻 Author Info
Name: Mohammed Khaleel Uddin

GitHub: @khaleeluddin9912

Date: April 10, 2025

📎 Repository Link
🔗 GitHub Repo: nginx-on-docker-with-terraform