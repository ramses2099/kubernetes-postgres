# kubernetes-postgres
Project kubernetes postgres SQL

## deployment kubernetes postgres sql


## create secret with the username and password
## Step 1: create secret
kubectl apply -f postgres-secret.yml

## apply the deployment kubernetes postgres
## Step 2: deploy kubernetes postgres
kubectl apply -f postgres-deployment.yml

## check the deployment kubernetes postgres
kubectl get deployments

## check the pods
kubectl get pods

## describe the pods
kubectl describe [pods-name]

## create configmap
kubectl apply -f postgres-configmap.yml

## asign public api address
microk8s service postgres-service

micro kubectl port-forward service\postgres-service 5432:5432

## enable hostpath-storage
microk8s enable hostpath-storage

## dashboard proxy
microk8s dashboard-proxy

https://10.0.0.50:10443