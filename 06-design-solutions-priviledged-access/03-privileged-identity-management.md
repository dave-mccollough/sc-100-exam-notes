# Privileged Identity Management

- [Link](https://learn.microsoft.com/en-us/entra/id-governance/privileged-identity-management/pim-configure)

- Privileged Identity Management (PIM)
  - PIM allows you to control, manage and monitor access to resources in your org
  - Resources include
    - Entra ID
    - Azure
    - Microsoft 365
    - Intune
    - Other Microsoft online services

- PIM Licensing
  - [Link](https://learn.microsoft.com/en-us/entra/fundamentals/licensing)
  - The following licenses will provide access to PIM functionality
    - Microsoft Entra ID 2
    - Microsoft Entra ID Governance

- PIM Features
  - Configure just in time (JIT) access to Entra ID and Azure resources
  - Create time bound access to resources with start and end dates
  - Enfore approval to activate privileged roles
  - Enforce MFA to activate a role
  - Utilize justification to understand why users activate
  - Receive notifications when privileged roles are activated
  - Conduct access reviews to ennsure users still need roles
  - Download audit history for internal or external audits

- Roles required to manage PIM
  - Manage assignments
    - Privileged Role Administrator
    - Global Adminstrator
  - View Assignments
    - Global Administrator
    - Privileged Role Administrator
    - Security Administrator
    - Global Reader
    - Security Reader

- Terminology
  - permanent eligble
    - Role assignement where user is always eligible to activate a role
  - permanent active
    - Role assignement where a user can always use a role without performing any actions
  - expire eligible
    - Role assignement where a user is elible to activate a role within a specified start and end date
  - expire active
    - Role assignemnt where a user can use the role without performing any actions within a specified start and end date
  - just in time access (JIT)
    - Users receive temporary permissions to perform privileged tasks
    - Access is granted only when users need it
  - principles of least privilege
    - Security practice where every user is provided with only the minimum privileges needed to accomplish their job
