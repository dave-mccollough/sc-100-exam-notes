# Conditional Access

- Conditional Access
  - A tool that leverages different signals for decision making
  - Determines whether to allow access, enforce certain policies, etc

- Common Signals
  - Identities
  - Endpoints
  - Applications 
  - Data
  - Infrastructure
  - Network

- Signal Examples
  - User or group membership
    - Can target specific users or groups
  - IP location information
    - Target IPs outside of trusted IP ranges
    - Can exclude countries, regions, etc
  - Devices
    - Target specific devices or platforms
  - Applications
    - Attempting to access specific applications can target different conditional access policies
  - Real time and calculated risk detection
  - Defender for cloud apps

- Common Decisions
  - Block Access 
    - Most restrictive
  - Grant access    
    - Less restrictive but can require one or more options
      - Require MFA
      - Require auth strength
      - Require device be compliant
      - Require Entra hybrid joined device
      - Require approved client app
      - Require app protection policy
      - Require password change
      - Require terms of use