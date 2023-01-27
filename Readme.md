Install kind on Mac
```
brew install kind
```
Install kubectl on Debian
```
apt-get install kind
```
Create a cluster

```
kind create cluster
```

create ingress controller
```
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/static/provider/kind/deploy.yaml
```
or 

```
kubectl apply -f nginx/ingress-controller.yaml

```
```
kubectl get pod
kubectl apply -f .
kubectl get pod
kubectl get configmap
kubectl get secret
kubectl get svc
kubectl get node -o wide
```
```
kubectl delete deployment --all
kubectl delete deployment --all -n ingress-nginx
```
```
kubectl delete secret --all
```
