# DevSecOps CICD Project Using Github Actions and ArgoCD
# Project Overview
This project aims to streamline deployment and management activities on AWS using a combination of IAM, Terraform, GitHub Actions, and Kubernetes
![gif2](https://github.com/cloudcore-hub/reactjs-quiz-app/assets/88560609/a0dfce93-3bde-45af-b82a-d7c9e2c47294)
# Key Components
- IAM User Setup: Creation of an `IAM user` with necessary permissions for AWS deployment and management.
- Infrastructure as Code (IaC): Utilization of `Terraform` and `AWS CLI`for setting up the Jumphost server `(EC2 instance)` on AWS..Used yet another Github workflow to automate it!(https://github.com/jignyasamishra/iac_code)
- GitHub Actions Configuration: Configuration of essential `GitHub Actions` workflows, including `Snyk`, `Docker`, `Sonarqube`, `Terraform`, `Kubectl`, `AWS CLI`, and `Trivy`.
- EKS Cluster Deployment: Deployment of an `Amazon EKS` cluster using `eksctl` commands.
- Load Balancer Configuration: Configuration of `AWS Application Load Balancer (ALB)` for the EKS cluster.
- Dockerhub Repositories: Automatic creation of repositories for frontend and backend Docker images on Dockerhub.
- ArgoCD Installation: Setup of `ArgoCD` for continuous delivery and GitOps.
- Sonarqube Integration: Integration of `Sonarqube` for `code quality` analysis
- Snyk Integration: Integration of `Snyk` for `vulnerability scanning` and `dependency management` analysis
- Trivy Integration: Integration of `Trivy` for `container image` and filesystem `vulnerability scanning`
- GitHub Action Pipelines: Creation of `GitHub Action` pipelines for deploying backend and frontend code to the EKS cluster.
- Monitoring Setup: Implementation of monitoring for the EKS cluster using `Helm`, `Prometheus`, and `Grafana`.
- ArgoCD Application Deployment: Deployment of the Three-Tier application, including database, backend, frontend, and ingress components, using ArgoCD.
- DNS Configuration: Configuration of DNS settings for application accessibility via custom subdomains.
- Data Persistence: Implementation of persistent volume and persistent volume claims for database pods to ensure data persistence.

# Application

 ![Screenshot from 2024-04-09 01-11-52](https://github.com/jignyasamishra/3-Tier-Architecture/assets/85229187/ccf1b0e9-01cb-4e75-8666-8e5c5d46a838)
 ![Screenshot from 2024-04-09 01-10-06](https://github.com/jignyasamishra/3-Tier-Architecture/assets/85229187/dca94eaa-276f-4222-ad1f-783de732da5b)
 ![Screenshot from 2024-04-09 01-09-16](https://github.com/jignyasamishra/3-Tier-Architecture/assets/85229187/b3517daf-4fb5-4d41-aa18-66abe4f3b208)
 ![Screenshot from 2024-04-09 01-08-17](https://github.com/jignyasamishra/3-Tier-Architecture/assets/85229187/48c8e19a-cc05-464a-8825-4a1f78f7394a)
 ![Screenshot from 2024-04-09 01-07-15 (1)](https://github.com/jignyasamishra/3-Tier-Architecture/assets/85229187/aa5ea115-1009-49fc-aa73-d87912acd1f7)
 ![Screenshot from 2024-04-09 01-07-50](https://github.com/jignyasamishra/3-Tier-Architecture/assets/85229187/71bf0669-8c30-422a-80ab-0d247ed843e0)
 ![Screenshot from 2024-04-09 01-07-36](https://github.com/jignyasamishra/3-Tier-Architecture/assets/85229187/6499b626-d55d-48dc-afd3-c7049f870e43)
 ![Screenshot from 2024-04-09 01-06-34](https://github.com/jignyasamishra/3-Tier-Architecture/assets/85229187/64056011-21f7-420c-829a-5e2eff2c13e5)
 
 Logged into the simple quiz application
 ![image](https://github.com/jignyasamishra/3-Tier-Architecture/assets/85229187/03ee20a0-219b-4d26-ba78-857fd695d0da)

# Conclusion and Monitoring
This project concludes with a summary of key achievements and ongoing monitoring of the EKS cluster’s performance using Grafana


