# ramen-k8s

## Prerequisites

- docker
- kind

```bash
$ kind create cluster --name ramen --config kind.yaml
$ kubectl apply -f deploy-ingress-nginx.yaml
```
