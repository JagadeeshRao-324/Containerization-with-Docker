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
- Azure DevOps organization with access to Azure Pipelines
- Docker installed on your build agent (e.g., Azure Pipelines hosted agent)
- An Azure Container Registry created
- An Azure Container Instance configured via pipeline

---

## Pipeline Workflow

1. **Build**: The React app is built and Docker image is created using the Dockerfile.
2. **Push**: The Docker image is pushed to the Azure Container Registry.
3. **Deploy**: The latest Docker image is deployed to Azure Container Instance.

---

![Image](https://github.com/user-attachments/assets/f1078b0f-2784-4de8-92dc-3e839aaa7de8)


<img width="959" alt="Image" src="https://github.com/user-attachments/assets/fcf57e39-85c1-4b17-92a3-5da3894ad9ab" />

![Image](https://github.com/user-attachments/assets/d942b08d-71d0-4ac3-a185-0655a695f8d9)
