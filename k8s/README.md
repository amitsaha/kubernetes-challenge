## Kubernetes deployment manifests

List of manifests:

- [Deployment manifest](./deployment.yaml)
- [Service manifest](./service.yaml)
- [Nginx ingress controller setup](./nginx-ingress-controller.yaml)
- [Ingress object for learn k8s application](./learnk8s-ingress.yaml)


To deploy:

```
$ kubectl apply -f deployment.yaml -f service.yaml
$ kubectl apply -f nginx-ingress-controller.yaml -f learnk8s-ingress.yaml
```

Access service from host: `curl $(minikube ip)`

