# Azure App Services 

- [Link](https://learn.microsoft.com/en-us/azure/app-service/overview)

- Azure App Services
  - A fully managed Platform as a Service (PaaS) solution that enables organizations to build, deploy, and scale web applications, REST APIs, and mobile backends without managing the underlying infrastructure.

- Capabilities
  - Managed Application Hosting
    - Hosts applications while Azure manages servers, operating systems, and infrastructure.
  - Multiple Language Support
    - Supports .NET, Java, Python, Node.js, PHP, and custom containers.
  - Automatic Scaling
    - Scales applications vertically or horizontally based on workload demand.
  - Security & Authentication
    - Supports Microsoft Entra ID authentication, managed identities, TLS, and network security controls.
  - CI/CD Integration
    - Automates deployments through GitHub Actions and Azure DevOps.
  - High Availability
    - Provides load balancing, deployment slots, and availability features based on the hosting tier.
  - Monitoring & Diagnostics
    - Integrates with Azure Monitor and Application Insights.
  - Network Integration
    - Supports Azure Virtual Networks, private endpoints, and isolated App Service Environments. 

- Use Cases
  - Web Application Hosting
    - Deploy websites and enterprise web applications.
  - API Hosting
    - Host RESTful APIs and backend services.
  - Mobile Backends
    - Support mobile applications with cloud-hosted services.
  - Enterprise Applications
    - Host internal business applications and customer portals.
  - Application Modernization
    - Migrate existing web applications to managed cloud infrastructure.
  - Development & Testing
    - Build, test, and deploy applications using staging environments.

- Shared Responsibility
  - Microsoft
    - Manages physical infrastructure, operating systems, platform maintenance, and underlying security.
  - Customer
    - Manages application code, data, identities, access controls, and application security configurations.

- Securing Azure App Services
  - Use Managed Identities
  - Implement Authentication and Authorization
  - Enable HTTPS and TLS/SSL
  - Configure IP restrictions and service endpoints
  - Secure Application Settings
  - Enable Application Firewall
  - Monitor and Audit activities