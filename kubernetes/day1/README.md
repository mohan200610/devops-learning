# Kubernetes Practical - Day 1

## Topics Learned

- Started Minikube Cluster
- Verified Kubernetes Node
- Viewed System Pods
- Created Standalone Pod
- Deleted Pod
- Learned the difference between Pod and Deployment

## Commands Practiced

```bash
minikube start --driver=docker
kubectl get nodes
kubectl get pods -A
kubectl run nginx --image=nginx
kubectl get pods
kubectl describe pod nginx
kubectl delete pod nginx
```

## Key Learning

- A standalone Pod is **not recreated** after deletion.
- A Deployment **automatically recreates** a Pod if it is deleted.
