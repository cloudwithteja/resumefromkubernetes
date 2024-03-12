This project contains files to host resume from Kubernetes using a loadbalancer.

step 1) Create a EKS cluster

step 2) Build a container image from dockerfile and push to dockerhub or ECR or any repsitory of one's choice.

step 3) Replace custom image details in image specification in loadbalancer.yaml file

step 4) deploy the pods,spin up a service using the yaml file.

step 5) access the load balancer url from browser to view resume
