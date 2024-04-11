# EKSMario

## Deployment steps

Navigate to root folder.

### Perform below terraform steps:

terraform init
terraform validate
terraform plan
terraform apply --auto-approve

### Additional Steps to redirect lb route to https:
If you have a domain configured on Route53, follow below link.

### Clean up
terraform destroy --auto-approve



