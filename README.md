# Wiki


## Deploy

### Kubernetes
Download [kompose.io](https://kompose.io/)

```
kompose convert
```

```
microk8s kubectl apply -fdb-service.yaml -f wiki-service.yaml -f db-deployment.yaml -f db-data-persistentvolumeclaim.yaml -f wiki-deployment.yaml -f wiki-ingress.yaml
```

This will allow the wiki to be configured on http://localhost:80

