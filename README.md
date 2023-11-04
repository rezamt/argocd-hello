# Hello ArgoCD
I have used the following tutorial : [Welcome to the Argo CD Tutorial](https://redhat-scholars.github.io/argocd-tutorial/argocd-tutorial/index.html)

![img.png](docs%2Fimg.png)

```
# Create an ArgoCD Application
kubectl apply -f apps/app.yaml

argocd app list
argocd app get argocd-hello
argocd app sync argocd-hello

```

