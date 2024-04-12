# Kubernetes DevSecOps CICD Project Using Github Actions and ArgoCD
# Project Overview
This project aims to streamline deployment and management activities on AWS using a combination of IAM, Terraform, GitHub Actions, and Kubernetes
![gif2](https://github.com/cloudcore-hub/reactjs-quiz-app/assets/88560609/a0dfce93-3bde-45af-b82a-d7c9e2c47294)
# Key Components
- IAM User Setup: Creation of an IAM user with necessary permissions for AWS deployment and management.
- Infrastructure as Code (IaC): Utilization of Terraform and AWS CLI for setting up the Jumphost server (EC2 instance) on AWS.
- GitHub Actions Configuration: Configuration of essential GitHub Actions workflows, including Snyk, Docker, Sonarqube, Terraform, Kubectl, AWS CLI, and Trivy.
- EKS Cluster Deployment: Deployment of an Amazon EKS cluster using eksctl commands.
- Load Balancer Configuration: Configuration of AWS Application Load Balancer (ALB) for the EKS cluster.
- Dockerhub Repositories: Automatic creation of repositories for frontend and backend Docker images on Dockerhub.
- ArgoCD Installation: Setup of ArgoCD for continuous delivery and GitOps.
- Sonarqube Integration: Integration of Sonarqube for code quality analysis in the DevSecOps pipeline.
- Snyk Integration: Integration of Snyk for vulnerability scanning and dependency management analysis in the DevSecOps pipeline.
- Trivy Integration: Integration of Trivy for container image and filesystem vulnerability scanning in the DevSecOps pipeline.
- GitHub Action Pipelines: Creation of GitHub Action pipelines for deploying backend and frontend code to the EKS cluster.
- Monitoring Setup: Implementation of monitoring for the EKS cluster using Helm, Prometheus, and Grafana.
- ArgoCD Application Deployment: Deployment of the Three-Tier application, including database, backend, frontend, and ingress components, using ArgoCD.
- DNS Configuration: Configuration of DNS settings for application accessibility via custom subdomains.
- Data Persistence: Implementation of persistent volume and persistent volume claims for database pods to ensure data persistence.
  
# Conclusion and Monitoring
This project concludes with a summary of key achievements and ongoing monitoring of the EKS cluster’s performance using Grafana


