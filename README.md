# 🚀 GitHub Actions DevOps Pipeline | Cloud & CI/CD Portfolio Project

![GitHub repo size](https://img.shields.io/github/repo-size/saiakhil-devops/github-actions-devops-pipeline)
![GitHub last commit](https://img.shields.io/github/last-commit/saiakhil-devops/github-actions-devops-pipeline)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/saiakhil-devops/github-actions-devops-pipeline/main.yml?label=CI%2FCD%20Pipeline)
![AWS Certified](https://img.shields.io/badge/AWS-Cloud%20Practitioner-%23FF9900?logo=amazonaws&logoColor=white)

---

## 📌 Overview

This repository is a **DevOps Portfolio Project** built to demonstrate my hands-on skills in CI/CD using **GitHub Actions**, containerization with **Docker**, and cloud fundamentals aligned with **AWS best practices**.

🔧 The pipeline is configured to:
- ✅ Automatically run unit tests on every push
- ✅ Perform Python linting using **Flake8**
- ✅ Format code with **Black**
- ✅ Build and test the app inside **Docker containers**
- ✅ Showcase real DevOps workflows that align with corporate standards

---

## ☁️ Technologies & Tools Used

| Category       | Tools & Services               |
| -------------- | ------------------------------ |
| 🛠 DevOps      | GitHub Actions, Docker         |
| 🧪 Testing     | `pytest`, unittest             |
| 🧼 Linting     | Flake8                         |
| 🎨 Formatting  | Black                          |
| 🐍 Language    | Python                         |
| ☁️ Cloud Ready | AWS, GitHub Packages, CI/CD    |

---

## 📂 Repository Structure

```bash
.
├── app/                 # Flask App code (Docker-ready)
├── tests/               # Python tests folder
├── .github/workflows/   # GitHub Actions workflows
├── Dockerfile           # Docker image definition
├── requirements.txt     # Python dependencies
└── README.md            # This file
```

---

## 🧠 What This Project Demonstrates

✅ **CI/CD Implementation:** End-to-end DevOps pipeline setup using GitHub Actions with build, test, lint, and format steps.

✅ **Hands-on Docker Experience:** Creating and deploying containerized applications for repeatable, scalable environments.

✅ **Test-Driven Development:** Writing and automating tests using Pytest with professional standards.

✅ **Real-World Git Workflows:** Clean and modular Git commits reflecting best practices.

✅ **AWS Practitioner Knowledge Applied:** Although this project runs on GitHub, the concepts are aligned with AWS-native implementations.

---

## 📊 Pipeline Flow Diagram

```mermaid
graph TD
    A[Code Push] --> B[GitHub Actions Trigger]
    B --> C[Run Unit Tests (Pytest)]
    C --> D[Run Flake8 Linting]
    D --> E[Run Black Formatter]
    E --> F[Docker Build]
    F --> G[CI/CD Status Badge Update]
```

---

## 🧾 Sample Output

> ✅ All GitHub Actions workflows are passing  
> ✅ Project is modular, containerized, and cloud-ready

---

## 🌟 Why This Matters

This project reflects my ability to independently build a CI/CD-ready application using real-world workflows. It demonstrates that I can:

- Understand end-to-end DevOps pipelines
- Align work with cloud-native tools and practices
- Communicate effectively through professional documentation
- Apply test-driven and standards-compliant development processes

---

## 🧠 About the Author

> **Sai Akhil Perumalla**  
> AWS Certified Cloud Practitioner ☁️  
> GitHub: [@saiakhil-devops](https://github.com/saiakhil-devops)  
> 📬 Email: saiakhilperumallaofficial@gmail.com

---

## 📣 Want to Connect?

If you're a recruiter, hiring manager, or fellow developer looking to collaborate or hire DevOps talent with practical GitHub Actions and cloud experience, feel free to reach out!
---

## 🧠 Technical Highlights

This project showcases real-world DevOps practices used in modern CI/CD pipelines. Below are the key technical elements:

### 🔸 GitHub Actions Workflows
- **Trigger Types:** Pull request, push to main, manual (workflow_dispatch).
- **Job Matrix:** Configurable jobs such as linting, formatting, testing using Python 3.10.
- **Action Steps:** Use of prebuilt and custom actions to ensure modular and scalable workflows.

### 🔸 Docker Integration
- Application containerization using a `Dockerfile` for portability.
- Ensures consistent environments across development, staging, and production.
- Pushes and pulls to Docker Hub (can be extended to ECR/GCR).

### 🔸 Linting & Code Formatting
- **Flake8:** Enforces code quality and stylistic consistency.
- **Black:** Auto-formats code to adhere to modern Python PEP8 guidelines.

### 🔸 Testing Strategy
- Python `unittest` module for automated test execution.
- Easily extendable to Pytest with HTML reporting or Allure.
- Test report logs stored with timestamps for debugging.

### 🔸 Cloud & DevOps Potential
- This project can be extended to deploy on **AWS EC2**, **Elastic Beanstalk**, or using **Terraform**.
- Demonstrates readiness for infrastructure-as-code and cloud-native applications.
- Integrates easily into DevOps stacks like Jenkins, CircleCI, or Azure DevOps.

---

## 🚀 Future Scope
- ☁️ Integration with AWS CodePipeline and CodeBuild
- 📊 Monitoring via Prometheus & Grafana
- 🔐 Secrets management via HashiCorp Vault or AWS Secrets Manager

---