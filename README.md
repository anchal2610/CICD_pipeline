# CICD_pipeline

In this project, we'll automate the build, test, and deployment processes for a Node.js web application.

Prerequisites:
Jenkins installed on a cloud VM.
A Node.js web application.
Docker (for containerization).
A GitHub repository to host the code.
Kubernetes cluster (either locally with Minikube or Docker Desktop, or a cloud provider like AWS, GCP, or Azure).

# Project Overview:
We'll build the CI/CD pipeline using Jenkins to automate the following processes:

Build the application in the pipeline.
Test the application (unit and integration tests).
Dockerize the application to ensure it can be deployed in a containerized environment.
Deploy the application to Kubernetes (staging first, then production).
Notify on pipeline status (success/failure).

# Step 1 
Dockerfile created for node.js code.
# Step 2
Set Up Jenkins on Linux EC2 Instance and access it on http://<EC2-Public-IP>:8080
# Step 3
Configure Jenkins Pipeline and write script
# Step 4
Written Kubernetes Deployment Configuration to deploy the app to the cluster
# Step 5
Run the Pipeline:
Make a change to the main branch of the repository and push it to GitHub.
Jenkins will automatically trigger the pipeline using the webhook from GitHub.

