# Docker Volumes

## Purpose
Docker volumes store persistent data.
Even if a container is deleted, the data remains in the volume.

## Commands

docker volume create mohan-data
docker volume ls
docker volume inspect mohan-data
docker volume rm mohan-data


# 🗄️ Docker Volumes

## 📖 Overview

Docker Volumes provide persistent storage for containers. Unlike container storage, data stored in a Docker Volume remains available even after the container is stopped or removed.

Persistent storage is essential for databases, logs, application files, and any data that should survive the container lifecycle.

---

## 🎯 Objectives

- Understand Docker persistent storage
- Create and manage Docker Volumes
- Inspect volume details
- Remove unused volumes
- Learn how Docker stores application data safely

---

## 🛠️ Commands Practiced

```bash
docker volume create mohan-data
docker volume ls
docker volume inspect mohan-data
docker volume rm mohan-data
```

---

## 📚 Key Concepts

- Volumes are managed by Docker.
- Data persists even if the container is deleted.
- Multiple containers can share the same volume.
- Volumes are preferred over bind mounts for production workloads.

---

## 💡 Real-World Use Cases

- MySQL Database Storage
- PostgreSQL Data
- MongoDB Data
- Jenkins Home Directory
- Application Logs
- User Uploaded Files

---

## ✅ Skills Learned

- Creating Docker Volumes
- Listing existing Volumes
- Inspecting Volume details
- Removing unused Volumes
- Understanding Persistent Storage

---

## 🚀 Next Step

Learn how Kubernetes uses Persistent Volumes (PV) and Persistent Volume Claims (PVC) for storage management.
