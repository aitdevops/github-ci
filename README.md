# 🚀 CI Setup for aitdevops-site

Welcome to the repository that manages CI workflows for the `aitdevops` project. This repository contains configurations for GitHub Actions. These workflows automate the process of building, pushing the docker image to artifact registry and update Helm values..

## 📂 Repository Structure

- `.github/workflows/` - Contains GitHub Actions workflows for building and pushing the docker image to artifact registry and update Helm values.

## 🛠️ CI Tools Overview

### 1. **GitHub Actions**

GitHub Actions is used to build and push the frontend docker image to artifact registry and update Helm values in the ArgoCD repository whenever changes are pushed to the frontend repository.

**Workflow File: `.github/workflows/ci.yml`**
