# 🚀 Chat App Deployment on Kubernetes

A Kubernetes deployment project for a real-time chat application, implementing a complete 3-tier architecture using microservices.

> **Original Chat Application developed by [Md. Afzal Hassan Ehsani](https://github.com/iemafzalhassan)**

## 📋 Project Overview

This project demonstrates the deployment of a full-stack chat application on Kubernetes, consisting of:
- React Frontend
- Node.js/Express Backend with Socket.io
- MongoDB Database

The deployment architecture leverages Kubernetes features to create a scalable, maintainable microservices infrastructure.

## 🏗️ Architecture
![Kubernetes Architecture Diagram](https://github.com/user-attachments/assets/133ca92a-1e09-4708-9676-a7ad0efc825a)

The deployment follows a 3-tier architecture pattern:
- Frontend tier (React)
- Backend tier (Node.js)
- Database tier (MongoDB)

Each component is:
1. Containerized using Docker
2. Deployed as Kubernetes Pods
3. Exposed via Kubernetes Services
4. Load balanced using Kubernetes Ingress

## ✨ Features

* **Containerized Microservices**: Each component runs in isolated containers
* **Kubernetes Native**: Utilizes k8s deployments, services, and pods
* **Scalable Architecture**: Easy horizontal scaling of frontend and backend services
* **Automated Deployment**: Kubernetes handles container orchestration
* **Service Discovery**: Internal service communication via Kubernetes DNS
* **Load Balancing**: Traffic distribution using Kubernetes services

## 🛠️ Tech Stack

* **Container Runtime**: Docker
* **Orchestration**: Kubernetes (Minikube)
* **Ingress Controller**: Nginx
* **Original App Stack**:
  * Frontend: React, TailwindCSS
  * Backend: Node.js, Express, Socket.io
  * Database: MongoDB

## 🔧 Prerequisites

* Kubernetes cluster (Minikube)
* kubectl CLI tool
* Docker
* Git

## 🚀 Deployment Status

Current deployment status in Kubernetes cluster:
- All pods running successfully
- Services properly configured
- Deployments maintaining desired replica sets
- Proper resource allocation and management

## 📝 Original Application

This deployment project builds upon the excellent chat application developed by Md. Afzal Hassan Ehsani. The original application features:
- Real-time messaging using Socket.io
- User authentication with JWT
- Modern UI with React and TailwindCSS
- Profile management
- Online status tracking

For more information about the original chat application, visit the [original repository](https://github.com/iemafzalhassan).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📱 Screenshots


<img width="1071" alt="Screenshot 2025-01-17 at 5 14 51 PM" src="https://github.com/user-attachments/assets/0e58c347-edd9-4c0f-a49e-0d95c712a547" />
<img width="1582" alt="Screenshot 2025-01-17 at 5 13 44 PM" src="https://github.com/user-attachments/assets/d3195738-6ffc-45ec-a8de-ba89ba934102" />
<img width="1582" alt="Screenshot 2025-01-17 at 5 11 33 PM" src="https://github.com/user-attachments/assets/d89b36f5-d35f-4aa7-ba70-0bfda1a8c402" />



## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

---
