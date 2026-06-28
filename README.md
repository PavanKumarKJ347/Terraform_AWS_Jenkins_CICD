# Terraform Jenkins CICD Pipeline

## This Project Can be Used to Provision Infrastructure With Terraform Using Jenkins.

## Terraform CICD Pipeline Stages

- Checkout Code from GitHub.
- Terraform Initialization.
- Terraform Validate.
- Terraform Plan.
- Terraform Apply.

### Tools and Technologies Used are Git, GitHub, Terraform, Jenkins and Amazon Web Services.

# Project Execution
## Git Checkout
```bash
  git branch: 'main', url: 'https://github.com/PavanKumarKJ347/Terraform_AWS_Jenkins_CICD.git'
```

## Terraform Initialization
```bash
  terraform init -no-color
```

## Terraform Validate
```bash
  terraform validate -no-color
```

## Terraform Plan
```bash
  terraform plan -no-color
```

## Terraform Apply
```bash
  terraform apply --auto-approve -no-color
```
### Infrastructure Should be Provisioned in Cloud Provider Using Jenkins.