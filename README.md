# 🚀 DevSecOps CI/CD Pipeline on AWS

> End-to-end DevSecOps pipeline built using Jenkins, SonarQube, Docker, Kubernetes, Terraform, Ansible and AWS.

---

## 📖 Project Overview

This project demonstrates a complete DevSecOps workflow for deploying a Spring Boot application on AWS.

The objective of this project is to automate the entire software delivery lifecycle—from infrastructure provisioning to application deployment—using modern DevOps tools and best practices.

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Cloud | AWS EC2 |
| CI/CD | Jenkins |
| Build Tool | Maven |
| Code Quality | SonarQube |
| Containerization | Docker |
| Container Orchestration | Kubernetes (Minikube) |
| Infrastructure as Code | Terraform |
| Configuration Management | Ansible |
| Version Control | Git & GitHub |

---

## 📂 Project Structure

```text
devsecops-pipeline/
│
├── ansible/
├── app/
├── docker/
├── jenkins/
├── kubernetes/
├── terraform/
├── docs/
└── README.md
```

---

## 🚧 Project Status

- ✅ Spring Boot Application
- ✅ Jenkins CI/CD Pipeline
- ✅ SonarQube Integration
- ✅ Docker Containerization
- ✅ Kubernetes Deployment
- ✅ Terraform Infrastructure
- ✅ Ansible Automation


---

## 🔄 CI/CD Workflow

The application follows an automated DevSecOps pipeline.

```text
Developer
    │
    ▼
Git Push
    │
    ▼
GitHub Repository
    │
    ▼
GitHub Webhook
    │
    ▼
Jenkins Pipeline
    │
    ├── Checkout Source Code
    ├── Build using Maven
    ├── Run Unit Tests
    ├── SonarQube Code Analysis
    ├── Build Docker Image
    └── Deploy Application
            │
            ▼
      Kubernetes Cluster
            │
            ▼
        Running Pods
            │
            ▼
        Kubernetes Service
            │
            ▼
          End Users
```
---

## ✨ Features

- Automated CI/CD pipeline using Jenkins
- Static code analysis with SonarQube
- Spring Boot application built using Maven
- Dockerized application deployment
- Kubernetes Deployment and Service
- Rolling updates with Kubernetes
- Self-healing Pods
- Infrastructure provisioning using Terraform
- EC2 configuration using Ansible
- GitHub-based source control

