### Flask API Deployment with Kubernetes

This repository serves as the completion for the Server Deployment, Containerization, and Testing project as part of the Udacity nanodegree. The Flask API has been successfully containerized and deployed to a Kubernetes cluster using Docker, AWS EKS, CodePipeline, and CodeBuild.

## Completed Tasks

Dockerfile Implementation
A Dockerfile has been crafted to encapsulate the Flask API. The Dockerfile ensures a smooth deployment by utilizing the production-ready Gunicorn server. This enhances the scalability and reliability of the application.

## Local Container Testing

The containerized Flask API has been thoroughly tested locally to ensure seamless functionality. Docker Desktop has been used to validate the API's health check (GET '/'), authentication endpoint (POST '/auth'), and content retrieval (GET '/contents'). The local development environment is fully operational.

## Initial Setup

Repository Forking:
The project repository has been forked to the GitHub account.

## Local Clone:
The forked repository has been cloned locally for further development.

## Project Files
# Relevant files for the completed project include:

```bash
.
├── Dockerfile 
├── README.md
├── aws-auth-patch.yml #ToDo (Completed)
├── buildspec.yml      #ToDo (Completed)
├── ci-cd-codepipeline.cfn.yml #ToDo (Completed)
├── iam-role-policy.json  #ToDo (Completed)
├── main.py
├── requirements.txt
├── simple_jwt_api.yml
├── test_main.py  #ToDo (Completed)
└── trust.json     #ToDo (Completed)
```

# Prerequisites Completed

All prerequisites for the project have been satisfied, including:

Docker Desktop installation
Git installation
Code editor setup (VS Code)
AWS Account configuration
Python version verification (between 3.7 and 3.9)
PIP upgrade to version 19.x or higher
Terminal setup (GitBash for Windows users)

# Command line utilities installation:

AWS CLI configuration
EKSCTL installation
KUBECTL installation

# Project Steps Accomplished

1. Dockerfile Implementation
The Dockerfile for the Flask API has been successfully written, ensuring a secure and efficient containerization process.

2. Local Container Testing
The container has been built and tested locally, confirming the flawless execution of the health check and API endpoints.

3. EKS Cluster Creation
A Kubernetes cluster on AWS EKS has been successfully created, providing a scalable environment for the Flask API.

4. Secret Storage
The Flask app's dependency on the JWT_SECRET has been addressed by securely storing it in the AWS Parameter Store.

5. CodePipeline Setup
A CodePipeline pipeline has been configured to trigger deployments upon GitHub check-ins, ensuring a continuous integration and deployment (CI/CD) pipeline.

6. CodeBuild Implementation
CodeBuild stages have been set up to build, test, and deploy the Flask API automatically, streamlining the development lifecycle.

For detailed insights into each step, refer to the project lesson.

This project stands as a testament to the successful deployment of a Flask API through containerization, emphasizing reliability, security, and continuous integration.

