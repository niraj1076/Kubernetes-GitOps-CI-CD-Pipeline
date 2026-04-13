# 🚀 Kubernetes GitOps CI/CD Pipeline (In Progress)

## 📌 Project Overview

This project demonstrates a modern GitOps-based CI/CD pipeline where application deployment is fully automated using Docker, Kubernetes, GitHub Actions, and ArgoCD.

The goal is to eliminate manual deployments and use Git as the single source of truth for infrastructure and application state.

---

## 🧱 Current Progress (PART 1 – Completed)

### ✅ Application Setup

* Created a simple static web application using HTML
* Designed for container-based deployment using Nginx

### ✅ Containerization using Docker

* Built a Docker image using a lightweight Nginx base image
* Configured Dockerfile to serve static content

### ✅ Local Testing

* Successfully ran the container locally
* Verified application accessibility on browser (`localhost:8080`)

### ✅ Image Registry Integration

* Tagged Docker image with version (`v1`)
* Pushed image to Docker Hub for remote access

---

## 🛠️ Tech Stack (So Far)

* Docker (Containerization)
* Nginx (Web Server)
* Git & GitHub (Version Control)

---

## 🔄 Workflow Achieved

Code → Docker Build → Local Test → Push to Docker Hub

---

## 🚧 Upcoming Implementation

### 🔹 PART 2 – Kubernetes Deployment

* Create Deployment & Service YAML
* Deploy application to cluster
* Expose service via Minikube

### 🔹 PART 3 – ArgoCD Setup

* Install ArgoCD in cluster
* Connect Git repository
* Enable GitOps-based deployment

### 🔹 PART 4 – CI Pipeline (GitHub Actions)

* Automate Docker image build & push
* Auto-update Kubernetes manifests

### 🔹 PART 5 – Full GitOps Flow

* Auto-sync deployments via ArgoCD
* Zero manual kubectl usage

---

## 🎯 End Goal

Push code → CI builds image → Image pushed to Docker Hub → Git updated → ArgoCD syncs → Application deployed automatically

---

## 📌 Status

🚧 In Progress (Currently completed: Docker setup & image deployment)

---

## 🧠 Learning Outcomes

* Understanding of containerization workflow
* Image versioning and registry usage
* Foundation for Kubernetes and GitOps pipeline
