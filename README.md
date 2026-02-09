# 3-Tier DevOps Project 🚀

This repository contains a **self-deployed 3-tier application** designed and implemented using **DevOps best practices**.  
The project demonstrates end-to-end CI/CD, containerization, infrastructure automation, and Kubernetes-based deployment on AWS.

---

## 🧱 Architecture Overview

The application follows a **3-tier architecture**:

1. **Frontend Tier**
   - React + Nginx
   - Dockerized frontend service
   - Exposed via Kubernetes Ingress

2. **Backend Tier**
   - Spring Boot microservices
     - Auth Service
     - Course Service
     - Enrollment Service
   - REST APIs
   - Dockerized and deployed on Kubernetes

3. **Infrastructure & Platform Tier**
   - AWS Cloud
   - Kubernetes (EKS)
   - Terraform for Infrastructure as Code
   - Jenkins for CI/CD pipelines

---

## 🛠️ Tech Stack

### Cloud & Infrastructure
- AWS (EKS, EC2, VPC, S3, IAM, Route53, CloudFront)
- Terraform (IaC)

### DevOps & CI/CD
- Jenkins
- Docker
- Kubernetes
- Helm (optional)
- Git & GitHub

### Backend
- Java
- Spring Boot
- Maven

### Frontend
- React
- Vite
- Nginx

---

## 📁 Project Structure

.
├── app
│ ├── frontend
│ ├── backend
│ │ ├── auth-service
│ │ ├── course-service
│ │ └── enrollment-service
│ ├── docker-compose.yml
│ └── k8s
│
├── infra
│ ├── global
│ ├── backend
│ ├── frontend
│ ├── modules
│ │ ├── vpc
│ │ ├── eks
│ │ ├── s3
│ │ ├── cloudfront
│ │ └── route53
│ └── terraform-backend
│
└── README.md
