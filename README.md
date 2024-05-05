```
registry-docker.cloud.lab
  docker-group (8082):
  - docker-proxy
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
```

```
upload-docker.cloud.lab
  docker-hosted (8085)
```

```
registry.cloud.lab
  registry (8088):
  - docker-proxy
  - quay-proxy
  - k8s-proxy
  - gcr-proxy
  - docker-hosted
```

