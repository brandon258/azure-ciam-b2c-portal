# Setup Guide: Azure CIAM B2C Portal

## Prerequisites

- Azure Subscription
- Azure AD B2C Tenant (use Microsoft 365 Dev Program)
- Terraform installed
- Microsoft Graph API permissions (via App Registration)
- PowerShell or Python installed

## Setup Steps

1. Deploy Azure AD B2C tenant using Azure Portal
2. Configure app registrations for:
   - Web App
   - Backend API
3. Clone this repo and set up Terraform variables
4. Run `terraform apply` in the `infra/` directory
5. Use scripts to manage users and groups
6. Test OIDC login via app (optional)

## Helpful Resources

- [Azure AD B2C Docs](https://learn.microsoft.com/en-us/azure/active-directory-b2c/)
- [Microsoft Graph API Explorer](https://developer.microsoft.com/en-us/graph/graph-explorer/)
- [Terraform Azure Provider](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs)
