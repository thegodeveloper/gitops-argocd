# gitops-argocd

## How to deploy

```shell
kustomize build apps/web/nginx/dev/do-nyc1-devops --enable-helm --load-restrictor LoadRestrictionsNone
```

## Notes about ArgoCD GitOps

![ArgoCD GitOps](img/argocd-gitops.png)