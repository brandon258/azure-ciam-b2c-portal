# azure-ciam-b2c-portal

A modern CIAM sandbox using Azure AD B2C, Microsoft Graph API, Terraform, and RBAC to simulate real-world customer identity solutions.

This project simulates a real-world Azure CIAM (Customer Identity & Access Management) environment using:

- **Azure AD B2C** for secure login, registration, and MFA
- **Microsoft Graph API** for user automation
- **Terraform** for Infrastructure-as-Code (IaC)
- **PowerShell / Python scripting** for RBAC and user lifecycle
- (Optional) **App frontend** to demonstrate OIDC login flow

## 🚀 Use Case

Demonstrate a complete CIAM flow for a sample application:

1. Users sign up via Azure B2C
2. Groups and roles assigned using Microsoft Graph
3. Admin portal automates user management
4. All infrastructure is provisioned with Terraform

## 📁 Project Structure

```text
azure-ciam-b2c-portal/
├── infra/         # Terraform IaC for Azure AD B2C
├── scripts/       # Graph API automation (PowerShell or Python)
├── app/           # Optional frontend app (e.g. React)
├── docs/          # Diagrams and documentation
└── .github/       # GitHub Actions

## 🔐 Identity Features

- OIDC sign-in/out
- Multi-Factor Authentication (MFA)
- Custom user attributes
- Group-based access control
- Conditional access policies

## 🛠 Tech Stack

- Azure AD B2C (Entra ID)
- Microsoft Graph API
- Terraform
- PowerShell or Python
- GitHub Actions

## 📚 Documentation

- [`docs/setup-guide.md`](docs/setup-guide.md)
- [`docs/architecture-diagram.png`](docs/architecture-diagram.png)
```
