# 🚀 GitHub Actions DevOps Pipeline

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/saiakhil-devops/github-actions-devops-pipeline/ci.yml?label=CI%20Status&style=flat-square)
![Docker](https://img.shields.io/badge/Dockerized-Yes-blue?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.10+-blue.svg?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/saiakhil-devops/github-actions-devops-pipeline?style=flat-square)

---

## 📘 Overview

This repository showcases a **complete CI/CD pipeline** implemented using **GitHub Actions**, integrated with a **Dockerized Flask application** and automated **Python code quality checks**. It serves as a **professional job portfolio project**, designed for aspiring **DevOps engineers, Cloud practitioners, and backend developers**.

The main goal is to simulate real-world DevOps workflows used in production environments—focusing on continuous integration, code quality enforcement, and deployment-readiness.

---

## 🧩 Key Features

| Feature                      | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| ✅ Continuous Integration    | Automatic testing, linting, and formatting on every push and PR             |
| 🐍 Python 3.10+              | Compatible with the latest Python standards                                 |
| 🧪 Pytest Testing            | Unit tests to ensure code reliability                                       |
| 🎨 Code Formatting           | Uses **Black** to auto-format code consistently                            |
| 🔍 Code Linting              | Applies **Flake8** for style and syntax enforcement                         |
| 🐳 Dockerized                | Flask app runs in a portable Docker container                              |
| 🤖 GitHub Actions            | Seamless CI configured in `.github/workflows/ci.yml`                       |
| 🌐 Cloud-Oriented            | Aligned with AWS/GCP/Azure DevOps practices                                |

---

## 🗂 Project Structure

```
github-actions-devops-pipeline/
├── .github/workflows/
│   └── ci.yml               # GitHub Actions CI workflow
├── app/
│   └── app.py               # Simple Flask application
├── tests/
│   └── test_sample.py       # Unit test for the app
├── Dockerfile               # Docker image configuration
├── requirements.txt         # Dependencies
└── README.md                # Project documentation
```

---

## 🧪 CI/CD Workflow Details

The GitHub Actions workflow (`ci.yml`) includes:

- 🔃 Triggered on push & pull requests to `main`
- 📦 Installs Python dependencies
- 🔎 Runs **flake8** for linting
- 🎨 Formats code using **black**
- ✅ Executes tests with **pytest**

---

## 💻 Local Development

### Requirements
- Python 3.10+
- Git & GitHub CLI
- Docker (optional but recommended)

### Steps

```bash
# Clone repository
git clone https://github.com/saiakhil-devops/github-actions-devops-pipeline.git
cd github-actions-devops-pipeline

# Setup virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run Flask app
python app/app.py

# Run tests
pytest
```

---

## 🐳 Running with Docker

```bash
# Build Docker image
docker build -t devops-pipeline-app .

# Run container
docker run -p 5000:5000 devops-pipeline-app
```

App will be accessible at `http://localhost:5000`

---

## 📈 Why This Project Matters

This project is designed to highlight your:

- ✅ Proficiency in **DevOps tooling**
- ☁️ Readiness for **cloud-native development**
- 🔄 Understanding of **CI/CD best practices**
- 🧠 Knowledge of **code quality gates**

Perfect for showcasing in job interviews or on your LinkedIn/GitHub profile.

---

## 🏷️ Badges of Practice

- ✅ **GitHub Actions CI**
- 🐳 **Dockerization**
- 📦 **Dependency Management**
- 📄 **Documentation and README excellence**
- 🧪 **Testing Coverage**

---

## 🧠 Technologies Used

- GitHub Actions
- Docker
- Python 3.10+
- Flask
- Pytest
- Flake8
- Black

---

## 🙌 Contributions

This project is self-developed as a job portfolio but contributions, feedback, and improvements are welcome! Fork the repo and start enhancing it.

---

## 📄 License

Licensed under the **MIT License**.

---

## 👤 Author

**Sai Akhil Perumalla**  
📍 Scarborough, Ontario, Canada  
📧 saiakhilperumalla@gmail.com  
🔗 [GitHub Profile](https://github.com/saiakhil-devops)  

---