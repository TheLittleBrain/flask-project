# flask-project

This is a simple project which shows how you can use the mentioned technologies below to create a DevOps environment.
This project automates the deployment of a AWS infrastructure for Flask application.

Technologies

AWS         [https://aws.amazon.com/]
AWS ECR     [https://aws.amazon.com/ecr/]
Flask       [https://flask.palletsprojects.com/]
Python      [https://www.python.org/]
Bash        [https://www.gnu.org/software/bash/]
Terraform   [https://www.terraform.io]
Docker      [https://www.docker.com/]
kind        [https://kind.sigs.k8s.io/]
Helm        [https://helm.sh/]
Jenkins     [https://www.jenkins.io/]
Git         [https://git-scm.com/]
Flask       [https://flask.palletsprojects.com/]


Deployment

Clone this repository
Modify the terraform.tfvars file with your desired infrastructure configuration
Run terraform init to initialize the Terraform module
Run terraform apply to apply the infrastructure changes
Use Helm to deploy the Flask application to the kind Kubernetes cluster


Management

Use Bash scripts for common infrastructure management tasks
Use Python scripts for custom infrastructure management tasks and integrations
Use Jenkins for continuous integration and delivery (CI/CD) pipelines
Use Docker for containerizing the Flask application
Use AWS ECR for storing the Docker images for the Flask application
Use the kind Kubernetes cluster for deploying and managing the containerized Flask application
Use Helm for managing the deployment of the Flask application on the Kubernetes cluster
Use Git for version control and collaborating with team members
