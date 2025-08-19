# GitHub Actions DevOps Pipeline

[![CI](https://github.com/saiakhil-devops/github-actions-devops-pipeline/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/saiakhil-devops/github-actions-devops-pipeline/actions/workflows/ci.yml)
[![CodeQL](https://github.com/saiakhil-devops/github-actions-devops-pipeline/actions/workflows/codeql.yml/badge.svg?branch=main)](https://github.com/saiakhil-devops/github-actions-devops-pipeline/actions/workflows/codeql.yml)
[![Trivy](https://github.com/saiakhil-devops/github-actions-devops-pipeline/actions/workflows/trivy.yml/badge.svg?branch=main)](https://github.com/saiakhil-devops/github-actions-devops-pipeline/actions/workflows/trivy.yml)
![Repo size](https://img.shields.io/github/repo-size/saiakhil-devops/github-actions-devops-pipeline)
![Last commit](https://img.shields.io/github/last-commit/saiakhil-devops/github-actions-devops-pipeline)
![License](https://img.shields.io/badge/license-MIT-informational)

A production-style, **zero-cost** CI/CD setup that demonstrates practical **DevSecOps**:
- Linting/tests with coverage artifacts  
- Static analysis with **CodeQL** (code scanning)  
- Container image scanning with **Trivy**  
- Clear docs, governance files, and reproducible local runs

> **Why it matters:** This mirrors real teams’ pipelines—automation, security gates, and documentation recruiters expect.

---

## Table of Contents
- [Quick Start (Local)](#quick-start-local)
- [Pipeline Overview](#pipeline-overview)
- [Repository Structure](#repository-structure)
- [Workflows](#workflows)
- [Badges (Fixing “unknown”)](#badges-fixing-unknown)
- [Development Guide](#development-guide)
- [Security & Compliance](#security--compliance)
- [Branch Protection (recommended)](#branch-protection-recommended)
- [Extending the Pipeline](#extending-the-pipeline)
- [AI Transparency](#ai-transparency)
- [Contributing](#contributing)
- [License](#license)

---

## Quick Start (Local)

```bash
# 1) Setup Python env
python -m venv .venv
# Windows: .venv\Scripts\activate
source .venv/bin/activate

# 2) Install deps if present
pip install -r requirements.txt || true
pip install -r requirements-dev.txt || true

# 3) Run tests with coverage (if tests exist)
pytest --cov=. --cov-report=term-missing --cov-report=xml
