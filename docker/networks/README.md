# Docker Networks

## Purpose
Docker networks allow containers to communicate with each other.

## Commands

docker network create my-network
docker network ls
docker network inspect my-network
docker network connect my-network mohan1
docker network connect my-network mohan2


# 🌐 Docker Networks

## 📖 Overview

Docker Networks allow containers to communicate securely with each other without exposing every service to the outside world.

Networking is one of the most important concepts in Docker because modern applications consist of multiple containers that must communicate.

---

## 🎯 Objectives

- Create custom Docker Networks
- Connect multiple containers
- Verify container-to-container communication
- Inspect Docker Network configuration

---

## 🛠️ Commands Practiced

```bash
docker network create my-network
docker network ls
docker network inspect my-network
docker network connect my-network mohan1
docker network connect my-network mohan2
```

---

## 🧪 Practical Exercise

Created two Ubuntu containers:

- mohan1
- mohan2

Connected both containers to the same custom bridge network.

Installed ping utility and successfully verified communication between the containers.

---

## 📚 Key Concepts

- Bridge Network
- Container Communication
- DNS-based Container Name Resolution
- Network Isolation
- Custom Networks

---

## 💼 Real-World Use Cases

- Frontend ↔ Backend Communication
- Backend ↔ Database Communication
- Microservices Architecture
- Secure Internal Networking

---

## ✅ Skills Learned

- Creating Docker Networks
- Connecting Containers
- Inspecting Network Details
- Testing Container Connectivity
- Understanding Docker Networking

---

## 🚀 Next Step

Learn Kubernetes Services and Ingress to understand networking in Kubernetes.
