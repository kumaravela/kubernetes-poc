# Kubernetes Microservices POC 🚀

## Overview
This POC demonstrates a full lifecycle of a cloud-native microservices system deployed on Kubernetes — covering developer, admin, and DevOps workflows.

## Features
- 3 microservices (User, Product, Order)
- Dockerized and deployed on Kubernetes
- Ingress-based routing with Nginx
- Horizontal Pod Autoscaling (HPA)
- RBAC and Secrets for security
- Prometheus + Grafana for observability
- GitHub Actions + ArgoCD for CI/CD

## Architecture
![Architecture Diagram](docs/architecture-diagram.png)

## Tech Stack
Kubernetes • Docker • Helm • ArgoCD • GitHub Actions • Prometheus • Grafana • Loki

## Setup
1. `minikube start`
2. `kubectl apply -f k8s-manifests/base/`
3. `kubectl apply -f k8s-manifests/*-service/`
4. Access app via Ingress: http://k8s-poc.local

## Author
Your Name — Kubernetes & Cloud-Native Enthusiast
