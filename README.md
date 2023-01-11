### Apply deployment and services


> kubectl apply -f deployment.yml -f service.yml
> minikube service backend

or

<code>
kubectl apply -f master-deployment.yml
</code>

### Delete and remove services

<code>
kubectl delete -f deployment.yml -f service.yml
<code>

or

<code>
kubectl delete -f deployment.yml, service.yml
<code>

or

Delete by selected label
<code>
kubectl delete -l group=example
</code>

or Delete by specified resources

<code>
kubectl delete deployments,service -l group=example
</code>
