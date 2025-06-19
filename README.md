# 📦 Cluster-Kubernetes
Este proyecto contiene la configuración necesaria para desplegar un microservicio desarrollado en Node.js usando Docker y Kubernetes en un clúster local con Minikube.

## 🚀 Tecnologías utilizadas
- 🐳 Docker
- ☸️ Kubernetes (kubectl)
- 📦 Minikube
- 🧠 Node.js + Express

## 🏗️ Estructura del proyecto
Cluster-Kubernetes/
├── Dockerfile
├── package.json
├── server.js
├── microservicio-deployment.yaml
├── microservicio-service.yaml
└── README.md

## 📌 Requisitos
- Docker
- Minikube
- kubectl
- Node.js (solo si desarrollas localmente)

## 🐳 1. Construir y subir la imagen Docker
# Construir imagen
docker build -t projecthackatom/microservicio:latest .

# Subir a Docker Hub
docker push projecthackatom/microservicio:latest
