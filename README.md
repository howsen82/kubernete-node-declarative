### Apply deployment and services

<blockquote>
kubectl apply -f deployment.yml -f service.yml
</blockquote>
<blockquote>
minikube service backend
</blockquote>

or

<blockquote>
kubectl apply -f master-deployment.yml
</blockquote>

### Delete and remove services

<blockquote>
kubectl delete -f deployment.yml -f service.yml
</blockquote>

or

<blockquote>
kubectl delete -f deployment.yml, service.yml
</blockquote>

or

Delete by selected label
<blockquote>
kubectl delete -l group=example
</blockquote>

or Delete by specified resources

<blockquote>
kubectl delete deployments,service -l group=example
</blockquote>
