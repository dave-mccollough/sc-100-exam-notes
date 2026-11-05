# Microsoft Sentinel Analytics Rules

- Designed to automatically detect potential security threats and anomalies
- Analyzes data collected from your environments
- Help identity suspicious activites, unusual patterns, known attack techniques and other indicators of compromise

- Types of analytics rules
  - Scheduled query rules
    - Run KQL queries at scheduled intervals to detect patterns or anamolies that match known threat signatures or suspicious behaviors
    - Microsft Incident Creation Rules
      - Automatically generate incidents from Microsoft 365 Defender alerts
    - Fusion Rules
      - Using AI to correlate and merge low fidelity, disparate alerts into high fidelity incidents
    - ML Behavior Analytics Rules
      - Use AI algorithms to identify unusual behaviors that deviate from established patterns
    - Near time analytics rules
      - Rule designed to detect threats and generate alerts quickly - almost as soon as data is ingested

- Customization and Configuration
  - Teams can create custom analytics rules specific to their environment or needs
  - Custom rules can be setup with various parameters
    - Severity levels
    - Event frequency
    - Threshold conditions

- Response Automations
  - Analytics rules can be integrated with automated response actions - Playbooks
  - Powered by Azure Logic Apps
  - Can perform a range of automated tasks when a rule is triggered

- Alerts and Incidents
  - When a analytics rule is triggered, it generates an alert
  - Alerts can be aggregated into incidents
  - Alerts can be consilidated into a view of related alerts for easier investigation and response 

- Continuous Improvement
  - Analytics can be regularly reviewed and modified
  - Continuous improvement helps maintain their effectivness