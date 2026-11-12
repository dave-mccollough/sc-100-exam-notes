# Sensitivity Labels in Purview

- [Link](https://learn.microsoft.com/en-us/purview/sensitivity-labels)

- Sensitivity Labels
  - Help orgs identify and label sensitive information
  - Using rules and conditions, data can be automatically labeled and classfied
  - Sensitivity labels can also be appliced to documents or emails by users

- How labels apply sensitivity
  - Labels are applied to documents and emails
  - Once labels are applied, classification information is identifiable regardless of where the data is stored or who shares it
  - Labels can include:
    - Visual markers on the header or footer
    - Watermark
  
  - Label Lifecycle
    - Admin 
       1. Creates a Sensitivity label
       2. Publishes the Sensitivity label to users and groups in the selected label policy
    - End User
       1. Classifies the email or document they are working on by applying a label     
    - Third party app or service
       1. Enforces protection settings on the email or document based on the applied label    

- Licensing Requirements
  - Office 365 E5/A5/G5
  - Microsoft 365 E5/A5/G5
  - Microsoft 365 E5/A5/G5/F5 Compliance
  - Microsoft 365 F5 Security and Compliance
  - Microsoft 365 E5/A5/G5 Insider Risk Management

- Assigning Sensitivity Labels
  - Customizable
    - Create labels specific to your org
      - Different catagories
      - Different levels of sensitive content
  - Clear Text
    - Labels are stored in clear text in the metadata
    - Third party apps or services can read it and apply their own actions
  - Persistant
    - Since the label is stored in metadata, it travels with the content regardless of where it is saved or stored
    - The label becomes the basis for applyting and enforcing policies you configure