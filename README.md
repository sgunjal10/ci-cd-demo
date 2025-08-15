# CI/CD Demo Project

A simple Python project with automated testing and Docker build using GitHub Actions.

## How to Run Locally
```bash
pip install -r requirements.txt
pytest
docker build -t ci-cd-demo .
