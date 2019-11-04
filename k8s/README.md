## Kubernetes deployment manifests

List of manifests:

- (./deployment.yaml)[Deployment manifest]
- (./service.yaml)[Service manifest]
- (./nginx-ingress-controller.yaml)[Nginx ingress controller setup]
- (./learnk8s-ingress.yaml)[Ingress object for learn k8s application]


To deploy:

```
$ kubectl apply -f deployment.yaml -f service.yaml
$ kubectl apply -f nginx-ingress-controller.yaml -f learnk8s-ingress.yaml
```

Access service from host: `curl $(minikube ip)`

