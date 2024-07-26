# Pre-requistes
1. minikube
2. kubectl

# Deployment
**start the deployment**

`kubectl apply -f deployment_nginx.yml`

# Service
**start the service**

`kubectl apply -f service_nginx.yml`

# Update
**update the index.html**

`kubectl cp index.html <--pod_name-->:usr/share/nginx/html/index.html `

where '<--pod_name-->' is the name of the pod

use

`kubectl get pods`

# URL 
**url to access in browser**

`minikube service nginx-test-service --url`
