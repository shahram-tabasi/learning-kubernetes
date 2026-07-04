if use private registry  ->  minikube addons configure registry-creds and minikube addons enable registry-creds

type minikube

chomd +x 

minikube start --force --insecure-registry "CIDR"

kubctl get po -A
kubctl get nodes
