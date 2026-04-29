# CI/CD Practice

## GitHub Secrets

Add the following repository secrets in GitHub (Settings  Secrets and variables  Actions):

- `EC2_HOST`: Public IPv4 address or DNS of the EC2 instance.
- `EC2_USER`: SSH username for the EC2 instance (for example, `ec2-user` on Amazon Linux).
- `EC2_SSH_KEY`: The private SSH key used to connect to the instance (the full key contents).
- `EC2_PORT`: SSH port (optional). Defaults to 22 if not set.
