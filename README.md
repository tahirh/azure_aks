# azure_aks

$rg=<resource-group>
$name=<cluster-name>

az login
az aks get-credentials --resource-group $rg  --name $name
kubectl get nodes
kubectl get pods


kubectl proxy

curl http://localhost:8001/api/v1

kubectl get pods -v=9



