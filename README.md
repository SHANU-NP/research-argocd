# research-argocd

direct k8s deployment commands

kubectl apply -f springboot-deployment.yaml
kubectl apply -f springboot-service.yaml

#for db connection : plannig to make local db as public uins ngrok

helm install springboot-app spring-boot-manifest/ -n dev  

kubectl get all -n dev   

helm ls -A 
