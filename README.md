# spring-kubernetes-teste

### Instructions Before 

- install: https://minikube.sigs.k8s.io/docs/start/

### Docker image
https://hub.docker.com/repository/docker/kalatunga/spring-kubernetes-teste

### Kubernetes
``` 
$ kubectl create deployment spring-kubernetes-teste --image=kalatunga/spring-kubernetes-teste:v1
$ kubectl expose deployment spring-kubernetes-teste --type=NodePort --port=9090
```

### API - endpoint

- access: http://[host Kubernetes>]:[port Kubernetes]/api/v1/ola
- My Kubernetes install, i accessed as follows -> http://192.168.49.2:31959/api/v1/ola
- Result: Olá Mundo!
