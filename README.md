# Pre-requistes
1. minikube
2. kubectl

# Deployment
**start the deployment**

`kubectl apply -f deployment_nginx.yml`

# Service
**start the service**

`kubectl apply -f service_nginx.yml`

# URL 
**url to access in browser**

`minikube service nginx-test-service --url`
