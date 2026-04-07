# goit-argocd

## Apply application
```kubectl apply -f application.yaml -n infra-tools```

## Check application
```kubectl get applications -n infra-tools```
```kubectl get pods -n application```
```kubectl get svc -n application```
## Access MLflow
```kubectl port-forward svc/mlflow -n application 5000:5000```

## Open:
```http://localhost:5000```

