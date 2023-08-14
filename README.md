# DevOps (DaaS) - Generate Credentials
GitHub Actions : DevOps As A Service (DaaS) - Generate Credentials

![GitHub Actions - Generate Credentials](https://github.com/emvaldes/generate-credentials/workflows/GitHub%20Actions%20-%20Generate%20Credentials/badge.svg)

---
### GitHub Actions (Required):

[System Requirements](https://github.com/emvaldes/system-requirements) -
[Marketplace](https://github.com/marketplace/actions/system-requirements)

---
### GitHub Secrets (Required):

```console
AWS_ACCESS_KEY_ID          Service-Account AWS Access Key-Id (e.g.: AKIA2...VT7DU).
AWS_SECRET_ACCESS_KEY      Service-Account AWS Secret Access Key (e.g.: zBqDUNyQ0G...IbVyamSCpe)

AWS_DEFAULT_ACCOUNT        The AWS Account number (e.g.: 123456789012).
```
---
### GitHub Variables (Required):

```console
AWSCLI_CLI                 Install Amazon WebServices CLI (false)
AWSCLI_DOWNLOAD            AWS CLI Download (awscli.amazonaws.com)
AWSCLI_PACKAGE             AWS CLI Package (e.g.: awscli-exe-linux-x86_64.zip)

AWS_DEFAULT_PROFILE        The AWS Credentials Default User (e.g.: default).
AWS_DEFAULT_REGION         The AWS Default Region (e.g.: us-east-1)
```

```console
CUSTOM_TOOLS               Install packages from custom list (default: null)
DEFAULT_TOOLS              Install packages from default list (default: null)

DEVOPS_ACCESS_ROLE         Defines the AWS IAM Role: DevOps--Custom-Access.Role
DEVOPS_ACCOUNT_NAME        A Deployment Service Account name (devops).

PRIVATE_KEYPAIR_FILE       Terraform AWS KeyPair (default: id_rsa)

PYTHON_REQUIREMENTS        Listing Python packages (default: null)

SANITIZE_OUTPUT            Sanitize Credentials Output (false)

TERRAFORM_CLI              Install Terraform CLI (false)
TERRAFORM_VERSION          Terraform specific target version (1.5.4)
```
```console
UPDATE_PIP                 Update Python package management (true)
UPDATE_PYTHON              Update Python to the latest version (true)

UPDATE_SYSTEM              Updating Operating System (false)
UPGRADE_SYSTEM             Upgrading Operating System (false)
```
```console
VERBOSE_MODE               Identify verbosity level (false)
```
