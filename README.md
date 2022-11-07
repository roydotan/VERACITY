# VERACITY


kubectl apply -f deployment.yaml  /n
kubectl apply -f service.yaml /n
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.44.0/deploy/static/provider/cloud/deploy.yaml
kubectl apply -f ingress.yaml
kubectl apply -f volume.yaml

