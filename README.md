# seldon

## Deploy
```
kubectl apply -f salary_lr_model.json
```

## Information of SeldonDeployment
```
kubectl describe seldondeployments salary-lr-model -n default
```

## Add Route


## Debug
```
kubectl get pods | grep salary
kubectl logs <salary-lr-model_pod_name>
```
