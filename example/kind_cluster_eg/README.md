Steps to Create yml File for K8s:

## To create config.yml file
```
vim config.yml
```
## To create cluster:
```
kind create cluster --name cluster123 --config=kind_cluster.yml
```
## To detail info of cluster:
```
kubectl cluster-info --context kind-cluster113
```

## To get detail of nodes:
```
kubectl get nodes
```