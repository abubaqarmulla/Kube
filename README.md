# Kube
minikube start 

minikube status

kubectl create deployment fun --image=nginx:latest

kubectl expose deployment fun --port=80

kubectl port-forward svc/fun 8080:80
