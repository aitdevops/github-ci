# 🚀 CI Setup for aitdevops-site

Welcome to the repository that manages CI workflows for the `aitdevops` project. This repository contains configurations for GitHub Actions. These workflows automate the process of building, pushing the docker image to artifact registry and update Helm values..

## 📂 Repository Structure

- `.github/workflows/` - Contains GitHub Actions workflows for building and pushing the docker image to artifact registry and update Helm values.
- In the next phase ArgoCD will deploy the images built by CI.

**Clone the repository FOR CD**:
   ```sh
   git clone https://github.com/aitdevops/argo-cd.git

## 🛠️ CI Tools Overview

### 1. **GitHub Actions**

GitHub Actions is used to build and push the frontend docker image to artifact registry and update Helm values in the ArgoCD repository whenever changes are pushed to the frontend repository.

**Workflow File: `.github/workflows/ci.yml`**
