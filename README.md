# Future Battlegrounds Kubernetes Config

## Deploying

```
kubectl apply -f ./future-battlegrounds.yml
kubectl apply -f ./future-battlegrounds-go-bot.yml
kubectl apply -f ./services/future-battlegrounds.yml
```

## Checking

```
kubectl port-forward deployment/future-battlegrounds-deployment 8080:8080
```

then try connecting with http://localhost:8080/swagger.html