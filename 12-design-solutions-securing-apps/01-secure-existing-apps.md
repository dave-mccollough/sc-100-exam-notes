# Secure Existing and Business Critical Apps

- [Link](https://learn.microsoft.com/en-us/azure/well-architected/security/secure-development-lifecycle)
- [Microsoft SDL](https://learn.microsoft.com/en-us/compliance/assurance/assurance-microsoft-security-development-lifecycle)

- Securing existing and business-critical applications involves implementing security controls throughout the Software Development Lifecycle (SDLC) to protect application code, sensitive data, infrastructure, and dependencies from vulnerabilities and cyber threats.

- Capabilities
  - Secure Development Lifecycle (SDL)
    - Integrate security into application design, development, testing, deployment, and maintenance.
  - Threat Modeling
    - Identify potential threats and security weaknesses early in application design.
  - Application Security Testing
    - Use static (SAST) and dynamic (DAST) testing to identify vulnerabilities.
  - Identity & Access Management
    - Enforce strong authentication, authorization, and least-privilege access.
  - Secrets Management
    - Protect credentials, certificates, and API keys using Azure Key Vault and managed identities.
  - DevSecOps Integration
    - Automate security scanning and validation within CI/CD pipelines.
  - Supply Chain Security
    - Identify vulnerabilities in third-party libraries, dependencies, and development tools.
  - Continuous Monitoring
    - Monitor applications for vulnerabilities, security threats, and configuration weaknesses.

- Use Cases
  - Legacy Application Security
    - Identify and remediate vulnerabilities in existing applications.
  - Business-Critical Application Protection
    - Strengthen security controls for applications supporting essential business operations.
  - Application Modernization
    - Integrate security improvements when migrating or modernizing applications.
  - Secure Software Development
    - Embed security testing and code reviews into development workflows.
  - DevSecOps Automation
    - Automate vulnerability detection and security checks before deployment.
  - Risk Reduction
    - Minimize application attack surfaces and protect sensitive business data.
  
- Microsoft Security Tools
  - Microsoft Defender for Cloud	
    - Cloud security posture and workload protection
  - GitHub Advanced Security	
    - Code, dependency, and secret scanning
  - Azure Key Vault	
    - Secure storage of application secrets and certificates
  - Microsoft Entra ID	
    - Authentication, authorization, and application identity
  - Azure Web Application Firewall	
    - Protection against common web application attacks
  - Azure Monitor	
    - Application monitoring and operational visibility