# helm-charts

## quick render test
```sh
helm template charts/app -f charts/app/values.yaml
```

## kubernets

### aws config
```sh
aws eks update-kubeconfig --region us-east-1 --name main --profile ticketpeak
```

### review pods
```sh
kubectl get pods -n production
```

### review pod logs
```sh
kubectl -n production logs ticketpeak-app-production-webapp-X-X
```
