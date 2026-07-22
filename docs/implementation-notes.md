## Deployment Workflow

1. Provision networking
2. Deploy EKS Cluster
3. Configure IAM Roles 
   # Create an IAM user in praf-identity
   # Create a User group
   # User Group 
     Terraform
   # IAM user 
     praf_terra
   # Attached policies
     AdministatorAccess
   # Tags 
     Terra (Terraform_Automation)
     



4. Build Docker Images
5. Push images to Amazon ECR
6. Deploy Kubernetes manifests
7. Validate workloads
8. Perform application testing
