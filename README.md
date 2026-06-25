# Python CI/CD Pipeline Project

An end-to-end CI/CD Pipeline project demonstrating automated build, containerization, and deployment of a Python application using **Jenkins**, **Docker**, **GitHub**, and **AWS**. This project showcases DevOps best practices, automation, and continuous integration workflows.

---

# Project Overview

This project automates the complete software delivery lifecycle of a Python application.

The CI/CD pipeline performs the following tasks:

- Retrieves the latest source code from GitHub
- Installs Python dependencies
- Builds a Docker image
- Pushes the Docker image to a container registry
- Deploys the application automatically
- Demonstrates DevOps automation using Jenkins Pipelines

---

# Tech Stack

- Python
- Jenkins
- Docker
- Git
- GitHub
- GitHub Actions
- AWS EC2
- Linux
- Shell Scripting

---

# Project Structure

```
python-cicd-project
│
├── app.py
├── Dockerfile
├── Jenkinsfile
├── Jenkinsfile-1for-ECR
├── Jenkinsfile-2
├── requirements.txt
└── README.md
```

---

# CI/CD Pipeline Workflow

```
Developer
     │
     ▼
GitHub Repository
     │
     ▼
Jenkins Pipeline
     │
     ├── Checkout Source Code
     ├── Install Dependencies
     ├── Build Docker Image
     ├── Run Unit Tests
     ├── Push Docker Image
     └── Deploy Application
              │
              ▼
           AWS EC2
```

---

# Features

- End-to-End CI/CD Pipeline
- Automated Source Code Checkout
- Dockerized Python Application
- Jenkins Pipeline Automation
- GitHub Integration
- AWS Deployment Ready
- Multiple Jenkins Pipeline Configurations
- Infrastructure Automation Ready

---

# Prerequisites

Before running this project, make sure the following software is installed:

- Git
- Docker
- Jenkins
- Python 3.x
- pip
- AWS EC2 Instance (Optional)

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/abhicy/python-cicd-project.git
```

## Navigate to the Project Directory

```bash
cd python-cicd-project
```

## Install Python Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

```bash
python app.py
```

---

# 🐳 Build Docker Image

```bash
docker build -t python-cicd-project .
```

---

# ▶️ Run Docker Container

```bash
docker run -d -p 5000:5000 python-cicd-project
```

---

# Jenkins Pipeline Stages

The Jenkins Pipeline includes:

- Source Code Checkout
- Dependency Installation
- Docker Image Build
- Docker Image Push
- Application Deployment
- Build Notifications

---

# AWS Deployment

The application can be deployed to an AWS EC2 instance using Jenkins Pipeline automation.

Deployment Steps:

- Launch EC2 Instance
- Configure Docker
- Configure Jenkins Agent
- Build Docker Image
- Push Image
- Deploy Container

---

# Project Screenshots

> Add screenshots here after completing the project.

Suggested screenshots:

- Jenkins Dashboard
- Successful Jenkins Build
- Docker Images
- Running Docker Container
- Application Running in Browser
- GitHub Repository
- AWS EC2 Deployment

---

# DevOps Skills Demonstrated

- CI/CD Pipeline Development
- Jenkins Automation
- Docker Containerization
- Git Version Control
- Linux Administration
- AWS EC2 Deployment
- Infrastructure Automation
- Continuous Integration
- Continuous Deployment

---

# Future Enhancements

- Kubernetes Deployment
- Helm Charts
- Terraform Infrastructure
- SonarQube Code Analysis
- Trivy Image Scanning
- Prometheus Monitoring
- Grafana Dashboard
- Argo CD GitOps Deployment

---

# Learning Outcomes

This project demonstrates practical knowledge of:

- DevOps Workflow
- CI/CD Automation
- Docker
- Jenkins
- GitHub
- AWS
- Linux
- Python Deployment

---

# 👨‍💻 Author

**Abhishek C Y**

📧 Email: abhicy111@gmail.com

🔗 GitHub: https://github.com/abhicy

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 📜 License

This project is intended for educational and learning purposes.
