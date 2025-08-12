# 🚀 My Terraform GitHub Repo

This repository was created to **manage GitHub resources** using [Terraform](https://www.terraform.io/).  
It’s a simple yet powerful example showing how Infrastructure as Code (IaC) can automate even your GitHub setup.

---

## 📌 Features
✅ Automatically creates a GitHub repository  
✅ Supports **public** and **private** visibility  
✅ Fully customizable using variables  
✅ Keeps configuration safe (no hardcoded secrets)  

---

## 🛠 How to Use

1. **Install Terraform**  
   [Download here](https://developer.hashicorp.com/terraform/downloads)

2. **Clone this repository**  
   ```bash
   git clone https://github.com/YourGitHubUsername/my-terraform-repo.git
   cd my-terraform-repo
## ⚙️ Configure your GitHub token

Edit the `terraform.tfvars` file:

```hcl
github_token = "ghp_yourTokenHere"
github_owner = "YourGitHubUsername"
```
▶️ Run Terraform

```bash
terraform init
terraform plan
terraform validate
terraform apply
```
👨‍💻 Author
Tejaswi Pathak
💼 DevOps Enthusiast | Cloud & Automation Engineer
🔗 GitHub | LinkedIn
