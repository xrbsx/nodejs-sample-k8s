# Exemplo app simples nodejs, docker, k8s.

## Execução

### Containerd

nerdctl run -p 49160:8080 -d xrbsx/app-nodejs-k8s

### K8s

kaf deploy.yaml

> Para acessar é necessário criar o service e o ingress

