# Day 8: Azure RBAC and Managed Identity

## Objective
Verify a user-assigned Managed Identity and its Azure RBAC role assignment.

## Lab Environment
- Resource Group: `RG-Azure-Lab`
- Managed Identity: `mi-az400-lab`
- Role: `Reader`
- Scope: `RG-Azure-Lab`

## Tasks Completed
1. Located the Managed Identity in Azure Portal.
2. Inspected the identity properties.
3. Verified the Reader role assignment in Access Control (IAM).
4. Used Azure CLI to verify the assignment.

## Result
The CLI query confirmed the Reader role at the Resource Group scope.

## Key Learning
An Azure RBAC role assignment consists of a security principal, role definition, and scope.

The Reader role provides read-only access to Azure resource management information. It does not automatically grant access to Blob data.

## Security Best Practices
- Follow the principle of least privilege.
- Avoid unnecessary role assignments.
- Never commit passwords, tokens, or private keys.

## Cost Considerations
No new virtual machine was required for this lab.
