# kubernatics
Learning of kubernatics with docket images

Install and pre-requiest: 
------------------------
a. basic of spring boot java. 
b. understanding of docker.
c. minicube install on system. ( check in kubernates.io web) 
d. kubectl install on system. 
e. docker install on system. 


Commands: 
---------
a. run docker :   $ docker run my_container
b. run minikubeL: $ minikube start 
c. run kubectl :  $ 

Start a new nginx web server in pods:
-------------------------------------
$ kubectl run --image=nginx web 
$ kubectl get pods
$ kubectl describe pod web 

