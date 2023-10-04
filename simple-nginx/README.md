- Deploy test my-app
```
kubectl create configmap index.html --from-file app/index.html
kubectl apply -k simple-nginx
```