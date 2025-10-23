# Kube
minikube start 

kubectl create deployment fun --image=nginx:latest

kubectl expose deployment fun --port=80

kubectl port-forward svc/fun 8080:80
