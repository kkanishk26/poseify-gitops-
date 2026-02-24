# Poseify DevSecOps GitOps Deployment

## 🚀 Project Overview

This project demonstrates an end-to-end DevSecOps GitOps pipeline using:

- Docker
- Kubernetes
- ArgoCD
- GitHub Actions
- DockerHub

The application is automatically deployed and synchronized to the Kubernetes cluster using GitOps principles.

---

## 🏗 Architecture

Developer Push → GitHub → GitHub Actions → DockerHub → ArgoCD → Kubernetes Cluster

---

## 🔁 Workflow

1. Developer pushes code to GitHub.
2. GitHub Actions validates the repository.
3. Docker image is stored in DockerHub.
4. ArgoCD monitors the Git repository.
5. Any changes in manifests are automatically synced to Kubernetes.
6. Application updates happen automatically without manual kubectl apply.

---

## ☸ Kubernetes Setup

- Deployment with scalable replicas
- NodePort service exposed
- Auto-sync enabled via ArgoCD
- Git as single source of truth

---

## 🔄 GitOps Auto Sync

- ArgoCD monitors the main branch
- Any commit updates the cluster state
- Replica scaling and configuration changes happen via Git

---

## 📦 Tech Stack

- Docker
- Kubernetes (k3s)
- ArgoCD
- GitHub Actions
- DockerHub

---

## 🎯 Key Features Implemented

✔ Containerized Application  
✔ Docker Image Push  
✔ Kubernetes Deployment  
✔ Service Exposure  
✔ ArgoCD GitOps Sync  
✔ CI Validation Workflow  
✔ Replica Scaling via Git  

---

## 📌 Result

Application successfully deployed with:

- Healthy status in ArgoCD
- Synced state
- Automated reconciliation
- Scalable replicas

---

## 👨‍💻 Author

Kanishk  
DevSecOps | Cloud | Kubernetes | GitOps
