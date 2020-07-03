# is-opa-gke

# STEPS

1) kubectl apply -f identity-namespace.yaml
2) kubectl apply -f identity-svc.yaml
3) kubectl apply -f identity-server-conf.yaml
4) kubectl apply -f identity-server-deployment.yaml
5) kubectl apply -f identity-wso2is-service.yaml
6) kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/static/provider/cloud/deploy.yaml
7) kubectl apply -f identity-server-ingress.yaml

Get the Host names and IP address
8) kubectl get ing -n wso2
Add wso2is <IP address> to /etc/hosts

https://wso2is/carbon/admin/login.jsp


