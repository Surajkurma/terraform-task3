# Terraform Docker Container

This project uses Terraform and the Docker provider to create a local Nginx container.

## Files

- `main.tf` — Terraform configuration for the Docker image and container.
- `execution.log` — Terraform state details recorded before cleanup.

## Steps performed

1. Initialized Terraform with `terraform init`.
2. Reviewed the proposed changes with `terraform plan`.
3. Created the Nginx image and container with `terraform apply`.
4. Checked Terraform state.
5. Removed the resources with `terraform destroy`.

The container mapped port 80 to host port 8080. The resources were destroyed after verification.