# Usage

this is a tutorial for kubernetes(minikube).
https://kubernetes.io/docs/tutorials/hello-minikube

```
initial
$ minikube start

# create deployment
$ kubectl create -f deployment.yml

# create service
$ kubectl create -f servive.yml

# display
$ minikube service node-app
```
