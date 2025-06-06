# React App Deployment with Docker, Azure Container Registry, and Azure Container Instance

This repository contains a React application that is containerized using Docker, pushed to Azure Container Registry (ACR), and deployed to Azure Container Instance (ACI) through an automated Azure Pipelines CI/CD process.

---

## Overview

- **React App**: The front-end application built with React.
- **Docker**: Used to containerize the React app.
- **Azure Container Registry (ACR)**: Stores the Docker image securely in Azure.
- **Azure Container Instance (ACI)**: Runs the containerized React app.
- **Azure Pipelines**: Automates the build, push, and deployment process.

---

## Prerequisites

- Azure subscription
- Azure CLI installed and logged in
- Azure DevOps organization with access to Azure Pipelines
- Docker installed on your build agent (e.g., Azure Pipelines hosted agent)
- An Azure Container Registry created
- An Azure Container Instance created or configured via pipeline

---

## Pipeline Workflow

1. **Build**: The React app is built and Docker image is created using the Dockerfile.
2. **Push**: The Docker image is pushed to the Azure Container Registry.
3. **Deploy**: The latest Docker image is deployed to Azure Container Instance.

---

## Usage

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-react-repo.git
cd your-react-repo
