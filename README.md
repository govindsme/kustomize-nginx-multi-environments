# Kustomize Demo

### Install kustomize CLI
```
 $ snap install kustomize 
```

### Build the manifests

```
$ kustomize build overlays/prod/|kubectl apply -f -
```

### Minikube

Get the minikube or cluster ip and access the application on your browser

```
$ minikube ip
```
