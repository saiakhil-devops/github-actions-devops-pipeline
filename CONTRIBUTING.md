# Contributing Guidelines

Thanks for your interest in contributing!

## Prerequisites
- Python 3.11+
- Git
- (Optional) Docker

## Local setup
```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
source .venv/bin/activate
pip install -r requirements.txt || true
pip install -r requirements-dev.txt || true
pip install pytest pytest-cov
