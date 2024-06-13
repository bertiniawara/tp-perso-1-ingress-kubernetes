# tp-perso-1-ingress-kubernetes

1. we begin by creating the kind cluster - ' kind create cluster --name=greatness --config=yen'
2. we then  check with ' kubectl get nodes '
3. next we create kubectl apply -f deployment.yaml
4. same for each other yaml 
5. finally execute kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/main/deploy/static/provider/kind/deploy.yaml
