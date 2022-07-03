# Kustomize Demo

### Install kustomize CLI
```
 $ snap install kustomize 
```

### Build the manifests

```
kustomize build overlays/prod/|kubectl apply -f -
```

