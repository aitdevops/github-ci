# 🚀 CI Setup for aitdevops

Welcome to the repository that manages CI workflows for the `aitdevops` project. This repository contains configurations for different CI tools, including GitHub Actions, CircleCI, Travis CI, and Jenkins. These workflows automate the process of building, testing, and deploying your application.

## 📂 Repository Structure

- `github-actions/` - Contains GitHub Actions workflows for building and deploying the application.
- `circleci/` - Placeholder for CircleCI configuration files.
- `travis/` - Placeholder for Travis CI configuration files.
- `jenkins/` - Placeholder for Jenkins pipeline configurations.
- `docs/` - Documentation and guides related to CI/CD processes.

## 🛠️ CI Tools Overview

### 1. **GitHub Actions**

GitHub Actions is used to build and push the frontend docker image to artifact registry and update Helm values in the ArgoCD repository whenever changes are pushed to the frontend repository.

**Workflow File: `.github/workflows/ci.yml`**
