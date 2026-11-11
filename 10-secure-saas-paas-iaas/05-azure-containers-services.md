# Azure Container Services

- [Link](https://learn.microsoft.com/en-us/azure/containers/)

- Azure Container Services
  - Cloud-based solutions for deploying, managing, and scaling containerized applications without managing all the underlying infrastructure. They support microservices, Kubernetes orchestration, and cloud-native application development.

- Capabilities
  - Container Hosting
    - Deploy and run containerized applications without managing physical servers.
  - Container Orchestration
    - Automate deployment, scaling, networking, and management using Kubernetes.
  - Automatic Scaling
    - Adjust compute resources based on application demand.
  - Microservices Support
    - Develop and deploy applications as independent, loosely coupled services.
  - Container Image Management
    - Securely store, manage, and distribute container images.
  - Security & Access Control
    - Integrate with Microsoft Entra ID, Azure RBAC, and Microsoft Defender for Cloud.
  - CI/CD Integration
    - Automate container builds and deployments through Azure DevOps and GitHub Actions.

- Core Azure Container Services
  - Azure Kubernetes Service (AKS)
    - Managed Kubernetes orchestration for complex container workloads
    - Azure Container Instances (ACI)	
      - Run containers on demand without managing servers
    - Azure Container Apps (ACA)
      - Serverless hosting for containerized applications and microservices
    - Azure Container Registry (ACR)
      - Store, secure, and manage container images
    - Azure Red Hat OpenShift (ARO)	
      - Enterprise Kubernetes platform based on Red Hat OpenShift
    - Azure App Service	Containers
      - Managed hosting for web applications and APIs, including custom containers

- Use Cases
  - Microservices Architecture
    - Build scalable applications using independent services.
  - Application Modernization
    - Migrate traditional applications into containers.
  - Web & API Hosting
    - Deploy containerized websites, APIs, and backend services.
  - DevOps Automation
    - Support CI/CD pipelines and automated application deployments.
  - Batch Processing
    - Run scheduled jobs and temporary container workloads.
  - Hybrid & Multicloud Applications
    - Deploy portable containerized workloads across environments.

- Security Considerations
  - Image Security
    - Scan container images for vulnerabilities.
    - Use trusted base images
  - Identity Management
    - Use Managed Identities - Integrate Entra ID
    - Enforce least-privilege access using Azure RBAC and managed identities.
  - Implement Network Security  
    - Restrict container communication and external exposure.
  - Runtime Protection
    - Monitor container workloads for suspicious activity.
  - Secrets Management
    - Protect application credentials using Azure Key Vault.
  - Encrypt sensitive data
  - Logging and monitoring
  - Apply security patches