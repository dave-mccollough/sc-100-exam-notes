# Sentinel Automation Rules

- [Link](https://learn.microsoft.com/en-us/azure/sentinel/create-manage-use-automation-rules?tabs=defender-portal%2Conboarded)

- Components of Automation Rules
  - Trigger
    - Defines what incident or event triggers the rule to run
      - When an incident is created
      - When an incident is updated
      - When an alert is created

  - Condition
    - Defines the circumstances under which the rule will perform
      - Equals or does not equal
      - Contains or does not contain
      - Starts with or does not start with
      - Ends with or does not end with

  - Action
    - Change the incident or call a playbook
      - Adding a task to an incident
      - Changing the status of an incident
      - Changing the severity of an incident
      - Assigning an incident a owner
      - Adding a tag to an incident