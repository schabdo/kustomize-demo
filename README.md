# Kustomize

Sandbox showcasing Kustomize

## Native

```bash
kustomize build overlays
```

```bash
kustomize build overlays/tenant-1
```

```bash
kustomize build overlays | kubectl apply -f -
```

## kubectl integration

```bash
kubectl apply -k overlays
```
