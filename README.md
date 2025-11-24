# starbucks-kubernetes-deployment
☕ Starbucks web application deployed on AWS EKS Kubernetes cluster with LoadBalancer service and auto-scaling capabilities.

# ☕ Starbucks Kubernetes Deployment

A modern cloud-native deployment of a Starbucks web application on AWS Elastic Kubernetes Service (EKS) with full CI/CD pipeline setup.

## 🚀 Features

- **Containerized Application**: Dockerized React application
- **Kubernetes Orchestration**: Deployed on AWS EKS cluster
- **High Availability**: Multi-pod deployment strategy
- **Load Balancing**: AWS LoadBalancer service configuration
- **Scalable Architecture**: Horizontal pod auto-scaling ready
- **Infrastructure as Code**: Kubernetes manifests for all resources

## 🛠 Tech Stack

- **Containerization**: Docker
- **Orchestration**: Kubernetes
- **Cloud Provider**: AWS EKS
- **Service Mesh**: LoadBalancer
- **Configuration**: YAML manifests
- **Version Control**: Git

## 📋 Prerequisites

- AWS Account with EKS access
- kubectl configured
- AWS CLI installed
- Docker experience

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/yourusername/starbucks-kubernetes-deployment.git

# Deploy to Kubernetes
kubectl apply -f k8s/

# Check deployment status
kubectl get all
