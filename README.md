# Notejam Django app @AWS

## Getting started

### Spin up the environment
    
1. `cd iac/`
2. `terraform workspace new _name_of_git_branch_` 
3. `terraform init`
4. `terraform apply`

Prerequisites:
- Install [terraform](https://learn.hashicorp.com/terraform/getting-started/install.html) >= v0.13 
- Install [aws cli](https://aws.amazon.com/cli/)
- Configure `notejam` aws profile by running `aws configure --profile notejam`
- Fill `iac/*.tfvars` files with desired values
