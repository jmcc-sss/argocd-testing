# Root Apps

These are the app of apps to deploy child apps.
This way we have a directory the root app watches, and it will create any child application placed in that directory.

## How to Deploy

```
# conntect to your AKS cluster
ctx aks-hub

# deploy the app-of-apps
kubectl apply -f aks-hub/argocd/root-apps/root-dops.yaml
```

## Reference

https://argo-cd.readthedocs.io/en/latest/operator-manual/cluster-bootstrapping/
https://www.reddit.com/r/kubernetes/comments/179nk1t/comment/k57weei
