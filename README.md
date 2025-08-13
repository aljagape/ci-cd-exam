# CI/CD Exam

This is a simple Node.js project with a basic CI/CD pipeline configured using GitHub Actions.

## CI/CD Workflow
The pipeline runs automatically on every push or pull request and does the following:
1. Installs dependencies with 'npm install'
2. Runs tests (if any) with 'npm test'
3. Performs a mock deployment by printing "Deploying..."

The workflow file is located at ".github/woprkflows/ci.yml'.

## How to run locally
```bash
npm install
npm test
