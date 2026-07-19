# AWS EKS Three-Tier Application

Production-inspired three-tier application deployed on Amazon EKS using Terraform, Kubernetes and AWS managed services.

## Objective

Design and deploy a production-inspired three-tier application on AWS using Infrastructure as Code and Kubernetes.

The project focuses on:

- Infrastructure provisioning using Terraform
- Container orchestration using Amazon EKS
- High Availability across multiple Availability Zones
- Secure networking
- CI/CD readiness
- Production deployment practices

## Architecture

Application Components

- Public Application Load Balancer
- Amazon EKS Cluster
- Frontend Deployment
- Backend API Deployment
- Database Layer
- Private Subnets
- NAT Gateway
- Internet Gateway
- Route Tables
- Security Groups

## Technologies

| Category | Technology |
|----------|------------|
| Cloud | AWS |
| IaC | Terraform |
| Containers | Docker |
| Orchestration | Amazon EKS |
| Networking | VPC |
| Registry | Amazon ECR |
| Monitoring | CloudWatch |
| Version Control | Git |


## Repository Structure
eks-three-tier/
README.md
terraform/
kubernetes/
applications/
docs/
images/
scripts/

## Deployment Workflow

1. Provision networking
2. Deploy EKS Cluster
3. Configure IAM Roles
4. Build Docker Images
5. Push images to Amazon ECR
6. Deploy Kubernetes manifests
7. Validate workloads
8. Perform application testing

## Current Progress

- [x] Repository initialized
- [ ] VPC
- [ ] Internet Gateway
- [ ] NAT Gateway
- [ ] Route Tables
- [ ] Security Groups
- [ ] IAM Roles
- [ ] Amazon EKS Cluster
- [ ] Worker Nodes
- [ ] Amazon ECR
- [ ] Frontend Deployment
- [ ] Backend Deployment
- [ ] Database
- [ ] Application Load Balancer
- [ ] Monitoring
- [ ] Documentation

## Future Improvements

- GitHub Actions
- ArgoCD
- Helm Charts
- Autoscaling
- Prometheus
- Grafana
- Blue/Green Deployments

## Lessons Learned

- Difference between NodePort and LoadBalancer
- Why private subnets require NAT Gateway
- IAM Roles for Service Accounts
- Kubernetes Networking
- Terraform State Management