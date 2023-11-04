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

I also ran my K8s cluster on top of : [Microk8s](https://microk8s.io/)


# References
- [canonical/microk8s](https://github.com/canonical/microk8s)
- [abiosoft/colima instead of Docker](https://github.com/abiosoft/colima)