# Azure Web Application Firewall

- [Link](https://learn.microsoft.com/en-us/azure/web-application-firewall/overview)

- Azure Web Application Firewall (WAF)
  - Cloud-based security service that protects web applications and APIs from common web attacks, vulnerabilities, and malicious HTTP/HTTPS traffic through centralized security policies and traffic inspection.

- Capabilities
  - Web Application Protection
    - Defends against common attacks such as SQL injection and cross-site scripting (XSS).
  - OWASP Protection
    - Uses managed rule sets aligned with common web application security risks.
  - Traffic Inspection
    - Analyzes incoming HTTP/HTTPS requests to identify and block malicious activity.
  - Custom Security Rules
    - Allows organizations to create rules based on IP addresses, geographic locations, and request characteristics.
  - Bot Protection
    - Helps detect and mitigate malicious automated traffic.
  - Rate Limiting
    - Restricts excessive requests to help mitigate application-layer attacks.
  - Monitoring & Logging
    - Integrates with Azure Monitor and Log Analytics for security visibility and investigation.
  - Centralized Management
    - Enforces consistent security policies across protected applications.
 
- Azure WAF Deployment Options
  - Azure Application Gateway	
    - Regional protection for web applications and APIs
  - Azure Front Door	
    - Global, edge-based protection for internet-facing applications
  - Application Gateway for Containers	
    - Protection for containerized applications
  - Azure CDN	
    - WAF protection for CDN-delivered content (preview)

- Use Cases
  - Web Application Security
    - Protect websites and applications from malicious requests.
  - API Protection
    - Detect and block attacks targeting HTTP-based APIs.
  - OWASP Threat Mitigation
    - Reduce exposure to common web application vulnerabilities.
  - Bot Mitigation  
    - Limit malicious bots and automated attacks.
  - Application Modernization
    - Add security controls to existing or migrated applications.
  - Compliance Support
    - Help meet application security requirements and industry standards.