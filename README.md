#  EKS 2048 Game Deployment

## Overview
This project demonstrates the deployment of the 2048 game on AWS EKS using Kubernetes and AWS Load Balancer Controller. The application is deployed using Kubernetes manifests and exposed publicly via an AWS Application Load Balancer (ALB).

---

##  Tech Stack
- AWS EKS
- Kubernetes
- kubectl
- eksctl
- Helm
- AWS ALB Ingress Controller

---

## 🚀Deployment Steps
1. Created EKS cluster using `eksctl`
2. Deployed 2048 application using Kubernetes YAML
3. Verified pods and deployment status
4. Installed AWS Load Balancer Controller using Helm
5. Created Ingress resource
6. Exposed application via AWS ALB

---

##  Project Files
- `2048_full.yaml` → Combined file containing:
  - Namespace
  - Deployment
  - Service
  - Ingress

---

##  Live Demo
👉 [Open the 2048 Game](http://k8s-game2048-ingress2-184c5765e8-54931241.us-east-1.elb.amazonaws.com/)

> ⚠️ Note: This is a temporary AWS Load Balancer link and works only while the EKS cluster is active.

---

## Proof of Deployment

###  Kubernetes Resources
- Deployment with 5 replicas
- Pods running successfully
- Ingress created using AWS ALB

###  Screenshot
![2048 Game Running](Screenshot.png)

---

## Key Learnings
- Kubernetes deployment and scaling
- AWS EKS cluster setup and management
- Ingress and Load Balancer integration
- Helm usage in real-world deployment
- Exposing applications using ALB

---

##  Future Improvements
- Split YAML into multiple files (Deployment, Service, Ingress)
- Add CI/CD pipeline
- Deploy custom application

---

##  Author
Priyanshi Saugat
