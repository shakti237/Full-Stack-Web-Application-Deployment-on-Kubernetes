# Full-Stack Web Application Deployment on Kubernetes

## Project Overview
This project demonstrates deploying a full-stack web application (React + Node.js + MongoDB) on Kubernetes with real-world production-level practices including containerization, persistent storage, and proper networking.

**Objective:**  
Deploy a multi-service application with Dockerized frontend and backend, a persistent database, and routing via Kubernetes Ingress.

---

## Tech Stack
- **Frontend:** React.js (Dockerized)
- **Backend:** Node.js + Express (Dockerized)
- **Database:** MongoDB (StatefulSet with persistent volume)
- **Containerization & Orchestration:** Docker & Kubernetes (Minikube)
- **Networking:** Kubernetes Service & Ingress
- **Tools:** kubectl, Docker, Minikube

---

## Features
- Multi-service architecture (Frontend + Backend + Database)
- Persistent storage using MongoDB StatefulSet
- Internal and external networking with NodePort and Ingress
- Dockerized containers for consistent deployment
- Easy scalability with Kubernetes Deployments
