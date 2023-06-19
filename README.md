# IUDX_Task

# Task Instructions
1) Pick a application/use your existing/easy to do projects from internet with following
criteria :
a) A basic HTTP web application in any language which takes some input
through an API endpoint and process it and store the data to db
b) The database can be mysql, psql, mongodb etc.
NOTE: We strongly suggest to pick application language and db which you are familiar
with for containerisation and deployment and we are not concerned with the code until
unless it meets the criteria above.
2) Containerise and deploy the above application components in local machine using
docker-compose
a) Refer docker docs and docker-compose docs
b) Expose the web application in docker to outside world, so that it can be
accessed through something like http://localhost:35622/xyz/
3) Containerise and deploy the above application in local K8s minikube cluster (using
kubectl only):-.
a) Please see the instructions on how to create a minikube on a local machine at
https://github.com/datakaveri/iudx-deployment/tree/master/K8s-deployment/K
8s-cluster/minikube .
b) Add auto scaling to any one of the components - web server or database.
c) Expose the web application in K8s to outside world, so that it can be
accessed through something like http://localhost:35622/xyz/ i.e. through
localhost of host machine
