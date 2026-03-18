# 🚀 DevOps CI/CD Kubernetes Pipeline

## 📌 Project Overview
This project demonstrates an end-to-end DevOps pipeline integrating Docker, Kubernetes, and GitHub Actions to automate application deployment.

---

## ⚙️ Tech Stack
- Docker 🐳
- Kubernetes (Minikube) ☸️
- GitHub Actions 🔄
- DockerHub 📦
- Flask (Python) 🐍

---

## 🧱 Architecture
Code → GitHub → CI/CD Pipeline → Docker Image → DockerHub → Kubernetes Deployment → Live Application


---

## 🚀 Features
- Automated CI/CD pipeline using GitHub Actions
- Containerized application using Docker
- Kubernetes deployment with multiple replicas
- Rolling updates for zero downtime deployment
- DockerHub integration for image storage

---

## 🔄 CI/CD Workflow
1. Developer pushes code to GitHub  
2. GitHub Actions triggers pipeline  
3. Docker image is built automatically  
4. Image is pushed to DockerHub  
5. Kubernetes deployment updated  

---

## 🛠️ Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/pranavisree/devops-ci-cd-kubernetes-pipeline.git
cd devops-ci-cd-kubernetes-pipeline

### 2. Build Docker Image
```bash
docker build -t devops-app .

### 3. Run locally
```bash
docker run -p 5000:5000 devops-app

### 4. Deploy to Kubernetes
```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

### 5. Access Application
```bash
minikube service devops-service

## 📸 Output

Displays:

CI/CD Auto Deployment Success 🚀
