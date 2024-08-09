# 🚀 CI Setup for aitdevops-site

Welcome to the repository that manages CI workflows for the `aitdevops` project. This repository contains configurations for GitHub Actions. These workflows automate the process of building, pushing the Docker image to the Artifact Registry, and updating Helm values.

## 📂 Repository Structure

- `.github/workflows/` - Contains GitHub Actions workflows for building and pushing the Docker image to the Artifact Registry and updating Helm values.
- In the next phase, ArgoCD will deploy the images built by CI in GKE with ingress-controller and cert-manager.

## 🛠️ How to Set Up CD

**Clone the repository for CD**:

```sh
git clone https://github.com/aitdevops/argo-cd.git
