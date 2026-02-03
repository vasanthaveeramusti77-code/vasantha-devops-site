# DevOps CI/CD Pipeline Project

## Overview
This project demonstrates a complete DevOps workflow using Docker, Kubernetes (Minikube), GitHub Actions, and NGINX.

## Tech Stack
- Docker
- Kubernetes (Minikube)
- GitHub Actions
- NGINX
- Linux
- GitHub

## Architecture
Developer → GitHub → CI/CD Pipeline → Docker Image → Kubernetes Deployment → Web App

## Features
- Automated Docker image build on every push
- Image pushed to Docker Hub
- Kubernetes deployment using YAML
- Exposed via Kubernetes Service

## How to Run Locally
```bash
minikube start
kubectl apply -f k8s.yaml
minikube service vasantha-site
