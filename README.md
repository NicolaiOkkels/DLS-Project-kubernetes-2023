## Docker images
```
docker run -p 5157 -d nho96/productupdateservice
docker run -p 8080:80 -d maja669e/wineshopfrontendservice
docker run -p 5000 -d erhanbasaran/adminservice
docker run -p 8081:80 -d alex8943/authenticationservice
docker run -p 8080:80 -d erhanbasaran/basketservice
docker run -p 8080:80 -d alex8943/authenticationservice
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
