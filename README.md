# Kustomize

Sandbox showcasing [Kustomize](https://kustomize.io)

## Native

```bash
kustomize build overlays/dev

kustomize build overlays/prod
```

```bash
kustomize build overlays/dev | kubectl apply -f -
```

## kubectl integration

```bash
kubectl apply -k overlays/dev
```

```bash
kubectl diff -k overlays/dev
```

## Links

* [Whitepaper](https://github.com/kubernetes/design-proposals-archive/blob/main/architecture/declarative-application-management.md)
* [Kustomize and Helm](https://github.com/kubernetes-sigs/kustomize/blob/master/examples/chart.md)
