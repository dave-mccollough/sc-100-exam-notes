# Microsoft Sentinel

- What is Microsoft Sentinel
  - Cloud based security information event management (SIEM)
  - Cloud based security orchestration automated response (SOAR)
  - Delivers security analytics and threat intelligence
  - Provides a centralized point for alert detection, threat visibility, proactive hunting and threat respoonse
  - Links to on-prem and third party services and products

- Cycle of Protection
  - Aggregates data from every user, device, app and infrastructure
    - On prem and in the cloud
  - Finds hidden threats and reduces false alarms
  - Uses AI to probe threats and looks for unusual behavior
  - Handles incidents with automated workflows and pre-programmed actions
  
  - Collect 
  - Detect 
  - Investigate
  - Respond 

- Data collection
  - Data is collected using data connectors
  - Several pre-configured connectors are available for services inside and outside the Microsoft ecosystem

- Automate and orchestrate
  - Use playbooks for task automation and security management
  - Use Azure Logic Apps to create playbooks

- Investigate

- Sentinel Requirements
  - Entra ID licence
  - Log analytics workspace

- I wrote a series of blog posts on Microsoft Sentinel a several years ago if their helpful
  - [Getting started with Azure Sentinel: Part 1](https://davemccollough.com/2020/11/14/getting-started-with-azure-sentinel-part-1/)
  - [Getting Started with Azure Sentinel: Part 2](https://davemccollough.com/2020/11/21/getting-started-with-azure-sentinel-part-2/)
  - [Threat Hunting with Azure Sentinel](https://davemccollough.com/2020/11/28/threat-hunting-with-azure-sentinel/)