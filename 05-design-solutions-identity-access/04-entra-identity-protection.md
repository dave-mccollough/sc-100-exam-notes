# Entra Identity Protection

- [Link](https://learn.microsoft.com/en-us/entra/id-protection/overview-identity-protection)

- Entra Admin Center -> ID Protection -> Risk based conditional access
- Entra Admin Center -> Entra ID -> Conditional Access

- Microsoft Entra Identity Protection
  - Helps organizations detect, investigate and remediate identity based attacks
  - Uses AI, User and expert generated feedback to create signals
  - Can be used with Conditional Access to make access decisions or ingested into a SIEM for further investigation
  
  - Risk Types:
    - Risky Users
      - User has one or more risky sign-ins
      - One or more risk detections have been reported
      - Detections
        - Possible attempt to access primary refersh token (PRT)
        - Anomalous user activity
        - User reported suspicious activity
        - Additional risk detected
        - Leaked credentials
        - Entra threat intelligence
    - Risky Sign-ins
      - Reported when one or more risk detections are reported for a sign-in
      - Detections
        - Atypical travel
        - Anomalous token
        - Malware linked IP address
        - Suspicious browser
        - Unfamiliar sign-in properties
        - Malicious IP address
        - Suspicious inbox manipulation rules
        - Password spray
        - Impossible travel
        - New country
        - Activity from anonymous IP address
        - Suspicious inbox forwarding
        - Mass access to sensitive files
        - Additional risk detected
        - Verified threat actor IP addres
        - Admin confirmed user compromised
        - Entra threat intelligence

    - Risky Apps

