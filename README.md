# Hello ArgoCD

```
# Create an ArgoCD Application
kubectl apply -f apps/app.yaml

argocd app list
argocd app get argocd-hello
argocd app sync argocd-hello

```