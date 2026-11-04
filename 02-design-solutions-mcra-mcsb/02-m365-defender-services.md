# M365 Defender Services

- What is Microsft 365 Defender
  - Comprehensive enterprise defense suite
  - Combines pre and post breach activities
  - Handles identification, prevention, examination and actions in response to security incidents across endpoints, user identities, email and applications
  - Holistic approach

## Defender Services

  - **Defender for Endpoint**
    - Endpoint behavior services
      - Integrated within Windows 10
      - Sensors capture and process behavioral data from the operating system
      - Data is captured by Defender for Endpoint
    - Cloud Security Analysis
      - Behavorial data is transformed into insights, detections and recommended responses
    - Threat Intelligence
      - Derived from Microsoft and trusted partners
      - Allows Defender for Endpoint to recognize attacker tactics, techniques and procedures
      - Triggers alerts when these are identified in the collected sensor data

  - **Defender for Office 365**
    - EOP (Exchange Online Protection)
      - Helps prevent broad volume based known attacks
    - Defender for Office 365 P1
      - Protects email and collaboration tools from zero day malware, phishing and business email compromise
    - Defender for Office 365 P2
      - Adds post breach investigation, hunting and response
      - Automation and Phishing simulation
    - Supports Teams, SharePoint, etc.

  - **Defender for Identity**
    - Formerly known and Azure ATP (Advanced Threat Protection)
    - Cloud based security solution for identity monitoring
    - Integrates with Microsoft 365 Defender
    - Utilizes data from on-prem AD and cloud based identities
    - Provides ITDR (Idenity threat detection) across hybrid environments
    - Conducts security posture assessments for identities
    - Real time detection of threats
    - Investigation of suspicious activities with incident information
    - Responds to attacks by automating responses to compromised identities

  - **Defender for Cloud Apps**
    - Formerly known as Cloud App Security
    - Protect SaaS apps and data
    - Integrates with Operating System to deploy policies to restrict certain activities

  - **Defender Vulnerability Management**
    - Provides asset visibility, intelligent evaluations and integrated remidation features
    - Works across Windows, MacOS, Linux, Android, iOS and network devices
    - Provides breach likelihood predictions, device assessments, business context insights
    - Ranks the most significant vulnerabilities on your assets
    - Provides guidance to mitigate potential risks

  - **Entra ID Protection**
    - Helps orgs identify and address identity related risks
    - Risks can be shared with SEIM or used for access control decisions

  - **Microsoft Data Loss Prevention (DLP)**
    - Using Microsoft Purview, DLP is implemented using DLP policies
    - Policies enable the identification, monitoring and automated protection of sensitive assets across:
      - Microsoft 365 Services
        - Teams
        - Exchange
        - SharePoint
        - OneDrive
      - Office applications
      - Endpoints running MacOS or Windows
      - Non Microsoft Apps
      - On-prem file repos and on-prem SharePoint
      - PowerBI

  - **App Governance**
    - Works with Defender for Cloud Apps
    - Security and policy management tolls for OAuth enabled apps registered on Entra, Google, etc
    - Overview of all non Microsoft apps registered with Entra ID, Google, Salesforce, etc with your org
    - Monitors app status and activities
    - Create proactive or reactive policies to address app or user behaviors
      - Protects agains noncompliant or malicious app usage
      - Restricts access to risky apps
    - Alerting and notification when unusla app activities occur
    - Automatic remediation capabilites