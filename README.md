# Centurion-LynxOps

![DevOps Racing Forza](file:///M:/B.Tech%20E-%20books%20(Centurion%20University%20of%20Technology%20&%20Managements)/3RD%20YEAR/5TH%20SEMESTER%20(CLOUD%20TECHNOLOGY%20DOMAIN)/CLOUD%20DEVELOPMENT%20&%20DevOps/forza.gif)


# 🚀 AWS DevOps Project – Centurion LynxOps

![AWS Cloud Logo](https://upload.wikimedia.org/wikipedia/commons/9/93/Amazon_Web_Services_Logo.svg)

---

## 📖 Overview
This repository documents **AWS DevOps workflows** and **Git integration** for cloud-native development and deployment.  
It serves as a guide for students and professionals working on **Cloud Technology & DevOps** projects.

---

## 🛠️ AWS DevOps Workflows

### 1️⃣ Infrastructure as Code (IaC)
- Use **AWS CloudFormation** or **Terraform** to define infrastructure.
- Automate provisioning of EC2, S3, RDS, and VPC resources.

### 2️⃣ Continuous Integration (CI)
- **AWS CodeCommit** → Source control.
- **AWS CodeBuild** → Automated builds and testing.
- **GitHub Actions** → CI pipelines integrated with GitHub.

### 3️⃣ Continuous Deployment (CD)
- **AWS CodeDeploy** → Deploy applications to EC2, Lambda, or ECS.
- **Elastic Beanstalk** → Simplified deployment for web apps.

### 4️⃣ Monitoring & Logging
- **Amazon CloudWatch** → Metrics and alerts.
- **AWS X-Ray** → Distributed tracing.
- **AWS Config** → Compliance monitoring.

---

## 🔑 Git Commands Cheat Sheet

| Command | Purpose |
|---------|---------|
| `git init` | Initialize a new Git repository |
| `git clone <repo-url>` | Clone a GitHub repository |
| `git status` | Check current changes |
| `git add .` | Stage all changes |
| `git commit -m "message"` | Commit changes |
| `git push origin main` | Push changes to GitHub |
| `git pull origin main` | Pull latest changes |
| `git branch -M main` | Rename branch to main |
| `git rm <file>` | Delete file from repo |

---

## 📂 Project Structure
```text
Centurion-LynxOps/
│── src/                # Source code
│── docs/               # Documentation
│── scripts/            # Automation scripts
│── .github/workflows/  # CI/CD pipelines
│── README.md           # Project guide
