```
registry-docker.cloud.lab
  docker-group (8082):
  - docker-proxy
  - docker-hosted
  - quay-group
  - k8s-group
```

```
registry-quay.cloud.lab
  quay-group (8083):
  - quay-proxy
```

```
registry-k8s.cloud.lab
  k8s-group (8084):
  - k8s-proxy
  - k8s-gcr-proxy
  - gcr-proxy
```

```
upload-docker.cloud.lab
  docker-hosted (8085)
```
