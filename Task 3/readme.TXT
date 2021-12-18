Here I used imparative commands rather than using declarative method
1- After installing and configuring minikube I ran "kubectl run hello --image=nginxdemos/hello  --port=80"
2- Then adding Nodeport after enabling ingress in minikube "kubectl expose pod hello --port=80 --type=NodePort" 
3- Then getting the service URL using "minikube service hello --url" and trying to curl on this URL