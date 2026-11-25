# `kubectl` Cheatsheet

A quick reference of common commands as I learn them.

## Cluster & Context
```bash
kubectl cluster-info
kubectl get nodes
kubectl config get-contexts
```

## Viewing Resources
```bash
kubectl get pods
kubectl get pods -A
kubectl get all
kubectl describe pod <pod-name>
kubectl logs <pod-name>
```

## Applying & Deleting Manifests
```bash
kubectl apply -f <file>.yaml
kubectl delete -f <file>.yaml
```

## Debugging
```bash
kubectl exec -it <pod-name> -- /bin/sh
kubectl get events --sort-by=.metadata.creationTimestamp
```
