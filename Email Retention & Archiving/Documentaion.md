## Project Overview
### Scenario
A financial services company must retain emails for 7 years due to compliance requirements. 
This project focuses on configuring Microsoft 365 Retention Policies and Archiving to ensure compliance with financial regulations.

### Solution Overview
This solution uses Microsoft 365 to create a 
* Retention Tag,
* Retention Policy
* Configure Archiving
* Enable Auto-Expanding Archive
* Litigation Hold

## Implementation
### *_Configuring Archiving for all users on Powershell_*
1. Open Powershell
2. Install Exchange Online
3. Import Exchange Online Module
4. Connect to Exchange Online
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/2228b84fc920dbcbc39e13ad4e31646a51b7d79e/Email%20Retention%20%26%20Archiving/Email%20Retention%20%26%20Archiving/archive1.jpeg)
---
5. Enabling Mailbox Archiving Using PowerShell (To automatically enable archive mailboxes for all users)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/2228b84fc920dbcbc39e13ad4e31646a51b7d79e/Email%20Retention%20%26%20Archiving/Email%20Retention%20%26%20Archiving/archive2.jpeg)
---
6. To check if archiving is enabled
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/2228b84fc920dbcbc39e13ad4e31646a51b7d79e/Email%20Retention%20%26%20Archiving/Email%20Retention%20%26%20Archiving/archive3.jpeg)

7. Enabling Auto-Expanding Archive

### *_Creating Retention Tags and Policies_*
8. Creating Retention Tags (to Move Emails to Archive After 7 Years)

9. Creating and Applying a Retention Policy (Creating a Retention Policy that includes the newly created tag)

10. Assigning the retention policy to all mailboxes

11. Verifying the Retention Policy (Check if the retention policy is applied)

### *_Verifying Litigation Hold done o prevent email deletion_*



