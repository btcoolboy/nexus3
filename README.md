```
registry-docker.cloud.lab
  docker-group (8082):
  - docker-proxy
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

