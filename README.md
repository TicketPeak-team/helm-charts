# helm-charts

## quick render test
```sh
helm template charts/app -f charts/app/values.yaml
```

## build
```sh
helm package charts/app
```

## kubernets pods
```sh
kubectl get pods -n staging
```
