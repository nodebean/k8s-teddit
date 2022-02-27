## Kubernetes teddit Example

### Purpose

Put teddit into a personal kubernetes cluster with an nginx sidecar

### Details
|File|Info|
|--|--|
|deployment.yaml|A teddit container and an nginx container with a volume mount and volume for the config  |
|service.yaml|service configuration|
|ingress.yaml|generic ingress configuration with tls |
|configmap.yaml|the configuration for the configmap that defines the mounted nginx.conf|
