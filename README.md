# Wiki


## Deploy

### Kubernetes
Download [kompose.io](https://kompose.io/)

```
kompose convert
```

```
microk8s kubectl apply -f db-data-persistentvolumeclaim.yaml -f db-data-persistentvolumeclaim.yaml -f wiki-deployment.yaml -f wiki-service.yaml
```

