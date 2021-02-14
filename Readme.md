# Gitlab runner in Kubernetes

##
1.   helm repo add gitlab https://charts.gitlab.io
2.   helm repo update
3.   kubectl create ns gitlab-runner
4.   helm install gitlab-runner --namespace gitlab -f values.yaml gitlab/gitlab-runner

 Create gitlab runner token as kubernets secrets and  Change values in values.yaml  
