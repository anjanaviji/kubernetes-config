# kubernetes-config
**1. Copy and run the commands in secrets_creation file**\
**2. Run the mysql.yaml file : `kubectl create -f mysql.yaml`**\
**3. Run frontend.yaml and backend.yaml:**<br/> 
-**`kubectl create -f frontend.yaml`**<br/> 
-**`kubectl create -f backend.yaml`**<br/> 
**4. Run the command `minikube addons enable ingress`**\
**5. Run ingress.yaml : `kubectl create -f ingress.yaml `**\
**6. curl localhost:80(hits frontend service), localhost/count(hits backend service)**
