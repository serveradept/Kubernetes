# Kubernetes Commands Cheat Sheet 📋

Welcome to the Kubernetes Commands Cheat Sheet! Below you'll find a collection of commonly used Kubernetes commands along with brief descriptions of their functionality.

## Pods 🚀

### List Pods
```sh
kubectl get pods
```
Lists all pods in the current namespace.

### Describe Pod
```sh
kubectl describe pod <pod-name>
```
Provides detailed information about a specific pod.

### Delete Pod
```sh
kubectl delete pod <pod-name>
```
Deletes a specific pod.

## Deployments 🛠️

### List Deployments
```sh
kubectl get deployments
```
Lists all deployments in the current namespace.

### Describe Deployment
```sh
kubectl describe deployment <deployment-name>
```
Provides detailed information about a specific deployment.

### Scale Deployment
```sh
kubectl scale deployment <deployment-name> --replicas=<replica-count>
```
Scales the number of replicas for a deployment.

### Delete Deployment
```sh
kubectl delete deployment <deployment-name>
```
Deletes a specific deployment.

## Services 🌐

### List Services
```sh
kubectl get services
```
Lists all services in the current namespace.

### Describe Service
```sh
kubectl describe service <service-name>
```
Provides detailed information about a specific service.

### Delete Service
```sh
kubectl delete service <service-name>
```
Deletes a specific service.

## Namespaces 🏷️

### List Namespaces
```sh
kubectl get namespaces
```
Lists all namespaces in the cluster.

### Describe Namespace
```sh
kubectl describe namespace <namespace-name>
```
Provides detailed information about a specific namespace.

## Configuration 🛠️

### View Cluster Info
```sh
kubectl cluster-info
```
Displays information about the Kubernetes cluster.

### View Nodes
```sh
kubectl get nodes
```
Lists all nodes in the cluster.

### View Configurations
```sh
kubectl config view
```
Displays the current Kubernetes configuration.

## Troubleshooting 🛠️

### View Logs
```sh
kubectl logs <pod-name>
```
Displays the logs of a specific pod.

### Exec into Pod
```sh
kubectl exec -it <pod-name> -- /bin/bash
```
Opens an interactive shell inside a specific pod.

### Port Forwarding
```sh
kubectl port-forward <pod-name> <local-port>:<remote-port>
```
Forwards traffic from a local port to a port on a specific pod.

## Conclusion 🎉

This cheat sheet covers some of the most commonly used Kubernetes commands. For more detailed information and additional commands, refer to the [official Kubernetes documentation](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands).

Happy Kuberneting! 🚀
