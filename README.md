# risk-pred
 
Deploy values.yaml file:
"helm upgrade --install risk-pred pingidentity/ping-devops -f values.yaml"

To Remove deployment:
"helm uninstall risk-pred"
"kubectl delete pvc --selector=app.kubernetes.io/instance=risk-pred"
