# Kubernetes 101

## Module 1
## Step 1: Cluster up and running
```
 microk8s version
```
## Step 2:
```
microk8s kubeclt version
```
## Step 3:
```
microk8s kubectl cluster-info
```
## Step 4:
```
microk8s kubectl get nodes
```
## Module 2
## Step 1 - Check application configuration
```
microk8s kubectl get pods
```
## Step 2:
```
microk8s kubectl describe pods
```


## port foward
kubectl port-forward service/postgresql-service 30080:5432