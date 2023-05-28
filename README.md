## Docker images
```
dockerhub nho96/productupdateservice
dockerhub maja669e/wineshopfrontendservice
dockerhub erhanbasaran/adminservice
dockerhub alex8943/authenticationservice
dockerhub erhanbasaran/basketservice
dockerhub alex8943/authenticationservice
```

## Kubernetes apply setup
```
kubectl apply -f admin-depl.yaml
kubectl apply -f basket-depl.yaml 
```
## Ingress Nginx controller installation
```
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.7.1/deploy/static/provider/cloud/deploy.yaml
```
