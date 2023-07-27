# Cloud-Native-Monitoring-Application
Deploying Flask Monitoring Application in Kubernetes Cluster

Prerequisites
Before you begin, ensure you have the following:

1. An AWS account with appropriate permissions to create EKS clusters and ECS repositories.</br>
2. The AWS CLI installed and configured with valid credentials.</br>
3. Docker installed on your local machine to build the Flask application's Docker image.</br>
4. Basic knowledge of Python, Flask, Kubernetes, and AWS services.</br>

Steps to deploy:
1. Clone the Repository
2. Build the Dockerfile
3. Log in to Amazon ECR
4. Build the Docker image for the Flask monitoring application
5. Push the Docker image to Amazon ECR
6. Create Amazon EKS Cluster
7. Deploy the Flask Monitoring Application to Kubernetes
8. Expose the Application
9. Access the Monitoring Application


Congratulations! You have successfully deployed a Flask monitoring application in your Amazon EKS Kubernetes cluster, </br>
utilizing Amazon ECS for storing the Docker image. The application allows you to monitor the cluster's health using CPU and Memory utilization gauges.</br>

Reference:</br>
Cloud Champ</br>
Source : https://www.youtube.com/watch?v=kBWCsHEcWnc&pp=ygUjY2xvdWQgbmF0aXZlIG1vbml0b3JpbmcgYXBwbGljYXRpb24%3D
