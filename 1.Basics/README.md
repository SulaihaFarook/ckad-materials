# Kubernetes Overview

## Container Orchestration
##### **Automatically deploying and managing container**

 *  Kubernetes  
 *  Docker swarm
 *  Mesos

## Kubernetes Architecture
![alt text](../1.Basics/images/basics.png)


## Pods
Create an NGINX Pod
```kubectl
kubectl run nginx --image=nginx
```

Create a deployment
```kubectl
kubectl create deployment nginx --image=nginx
```
