# Argo CD

### Create a project
```bash
kubectl -n <argo-cd namespace> apply -f project.yaml
```

### Create a repository
```bash
argocd login <argocd.url.com>
argocd repo add <git repo>
```