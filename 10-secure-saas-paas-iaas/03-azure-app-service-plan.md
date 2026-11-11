# Azure App Service Plans

- [Link](https://learn.microsoft.com/en-us/azure/app-service/overview-hosting-plans)

- Azure App Service Plans
  - Defines the compute resources, pricing tier, operating system, and scaling capabilities used to host web applications, APIs, and other supported workloads in Azure App Service.

- Capabilities
  - Compute Resource Management
    - Defines CPU, memory, and virtual machine instances available to applications.
  - Application Hosting
    - Supports web applications, REST APIs, and backend services.
  - Scalability
    - Allows vertical scaling (larger instances) and horizontal scaling (additional instances).
  - Resource Sharing
    - Multiple applications can share compute resources within the same App Service Plan.
  - High Availability
    - Supports features such as autoscaling and deployment slots, depending on the tier.
  - Cost Management
    - Provides different pricing tiers based on performance, capacity, and required features.
  - Network Isolation
    - Supports dedicated and isolated hosting environments.

- App Service Pricing Tiers
- Free / Shared
  - Development, testing, and low-traffic applications
  - Basic	
    - Small production workloads requiring dedicated compute
  - Standard
    - Production applications requiring autoscaling and deployment slots
  - Premium (v2/v3/v4)	
    - High-performance applications requiring greater capacity and advanced scaling
  - Isolated v2
    - Enterprise applications requiring dedicated network isolation

- Use Cases
  - Web Application Hosting
    - Deploy and manage websites and web applications.
  - API Hosting
    - Host backend APIs and application services.
  - Development & Testing
    - Run applications in nonproduction environments.
  - Enterprise Applications
    - Host scalable, business-critical applications.
  - Application Consolidation
    - Host multiple applications on shared compute resources to optimize costs.

- Considerations
  - Applications within the same plan share underlying compute resources.
  - Scaling a plan generally affects all applications hosted within it.
  - Dedicated tiers are billed based on provisioned compute resources, even when applications are idle.
  - Separate plans can provide independent scaling and resource isolation.