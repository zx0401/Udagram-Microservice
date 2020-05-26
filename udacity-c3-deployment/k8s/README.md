### Environment Variables:
You'll need to provide the information in the following files:
aws-secret.yaml
env-secret.yaml
env-configmap.yaml

### Deploy the applicatioon to the cluster
You'll need to install the kubectl first and run:

  - kubectl apply -f udacity-c3-deployment/k8s/aws-secret.yaml
  - kubectl apply -f udacity-c3-deployment/k8s/env-configmap.yaml
  - kubectl apply -f udacity-c3-deployment/k8s/env-secret.yaml
  - kubectl apply -f udacity-c3-deployment/k8s/backend-feed-deployment.yaml
  - kubectl apply -f udacity-c3-deployment/k8s/backend-user-deployment.yaml
  - kubectl apply -f udacity-c3-deployment/k8s/frontend-deployment.yaml
  - kubectl apply -f udacity-c3-deployment/k8s/reverseproxy-deployment.yaml
  - kubectl apply -f udacity-c3-deployment/k8s/backend-feed-service.yaml
  - kubectl apply -f udacity-c3-deployment/k8s/backend-user-service.yaml
  - kubectl apply -f udacity-c3-deployment/k8s/frontend-service.yaml
  - kubectl apply -f udacity-c3-deployment/k8s/reverseproxy-service.yaml

