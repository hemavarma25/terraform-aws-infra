# Terraform AWS Infrastructure

Project 2 in my DevOps/Cloud Engineering learning path: rebuild the AWS web app infrastructure from Project 1 as code using Terraform, to practice Infrastructure as Code.

## Goals
- Learn Terraform basics: providers, resources, variables, outputs
- Codify VPC, subnet, security group, and EC2 provisioning
- Practice the terraform plan/apply/destroy workflow

## Todo
- [ ] Set up Terraform and AWS provider configuration
- [ ] Write Terraform resources for VPC, subnets, and route tables
- [ ] Write Terraform resource for security groups (SSH/HTTP)
- [ ] Write Terraform resource for EC2 instance with user-data to install a web server
- [ ] Use variables for configurable values (region, instance type, etc.)
- [ ] Add outputs (e.g., public IP of instance)
- [ ] Run terraform plan and apply to provision infrastructure
- [ ] Verify the deployed web app works
- [ ] Run terraform destroy to tear down and confirm clean removal
- [ ] Document the Terraform workflow in the README
