# Kubernetes-Cluster/mongodb-mongoExpress/Docker-images
![image](https://user-images.githubusercontent.com/66872323/178170443-19d86673-7d1c-415b-9ccf-22dd16c9033d.png)

### kubectl apply commands in order
    
    kubectl apply -f mongo-secret.yaml
    kubectl apply -f mongo.yaml
    kubectl apply -f mongo-configmap.yaml 
    kubectl apply -f mongo-express.yaml

### kubectl get commands

    kubectl get pod
    kubectl get pod --watch
    kubectl get pod -o wide
    kubectl get service
    kubectl get secret
    kubectl get all | grep mongodb

### kubectl debugging commands

    kubectl describe pod mongodb-deployment-xxxxxx
    kubectl describe service mongodb-service
    kubectl logs mongo-express-xxxxxx

### give a URL to external service in minikube

    minikube service mongo-express-service

### Cluster-DashBoard command

    minikube dashboard

![image](https://user-images.githubusercontent.com/66872323/178170616-c98be734-ed2f-4811-8ac4-a9858846b1b0.png)
ed
