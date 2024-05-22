# k8s-nginx
Nginx App on K8s cluster
```
git clone https://github.com/atulkamble/k8s-nginx.git
cd .\k8s-nginx\
code .
```
```
New-Item nginx-deployment.yaml
kubectl create -f .\nginx-deployment.yaml
New-Item nginx-service.yaml
kubectl apply -f .\nginx-service.yaml
kubectl get pods
kubectl get services
minikube service nginx-service
```
