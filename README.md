# helm-charts

## quick render test
```sh
helm template charts/app -f charts/app/values.yaml
```

## build
```sh
helm package charts/app
helm repo index packages/ --url packages --merge index.yaml
mv packages/index.yaml index.yaml
```

## kubernets pods
```sh
kubectl get pods -n staging
```
