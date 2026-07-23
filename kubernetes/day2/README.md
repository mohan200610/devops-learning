# Kubernetes Practical Day 2 - ReplicaSet

## Topics Covered

- ReplicaSet
- Deployment and ReplicaSet
- Pod Recreation
- Pod Template

## What I Learned

- ReplicaSet creates Pods.
- ReplicaSet recreates Pods if a Pod is deleted.
- ReplicaSet maintains the desired number of Pods.
- Deployment manages ReplicaSets.
- Deployment provides scaling, rolling updates, and rollback.
- ReplicaSet uses the Pod Template to create identical Pods.

## Commands

kubectl get rs

kubectl describe rs

kubectl delete pod <pod-name>

kubectl get pods -w# Kubernetes Practical Day 2

## Topics Covered

- ReplicaSet
- Pod Recreation
- Pod Template
- Deployment vs ReplicaSet
- Labels & Selectors

## Commands

kubectl get rs

kubectl describe rs

kubectl delete pod

kubectl get pods -w

## Learning Outcome

- Understood ReplicaSet architecture.
- Learned how ReplicaSet recreates Pods.
- Learned Deployment controls ReplicaSet.
