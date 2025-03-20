# Implementing Phishing Protection in M365

## Problem Statement
A company is experiencing an increase in phishing emails, posing a significant security risk. The security team needs to implement protection mechanisms to reduce phishing risks in M365.

## Solution Overview
This solution utilizes Microsoft 365 (M365) security features to protect against phishing attacks. The implementation involves:

1. **Microsoft Defender for Office 365**: Configuring anti-phishing policies and settings to detect and block phishing emails.
2. **Exchange Online Protection (EOP)**: Setting up anti-phishing rules and filters to further enhance email security.
3. **Entra ID (formerly Azure Active Directory)**: Implementing multi-factor authentication (MFA) and conditional access policies to reduce the risk of compromised accounts.

## Implementation Steps
## Step 1: Configuring Microsoft Defender for Office 365
* **_Setting up anti-phishing rules and settings_**
![image alt](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/antipolicy1.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/antipolicy2.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/antipolicy3.png)


* **_Created a safe link policy to protect users from malicious URLs_**
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/safelink1.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/safelink2.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/safelink3.png)


* **_Configured a safe attachment policy to protect users from malicious email attachments_**
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/safeattach1.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/safeattach2.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/safeattach3.png)


* **_Implementing of Zero-hour Auto Purge (ZAP) for Anti-Spam by moving delivered messages in mailboxes to the Junk Email folder or quarantine if found to be spam, phishing, or contain malware_**
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/antispam1.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/antispam2.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/antispam3.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/antispam4.png)


* **_Enabled Microsoft Defender Attack Simulation Training_**
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/attacksim1.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/attacksim2.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/attacksim3.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/attacksim4.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/attacksim5.png)


## Step 2: Setting up Exchange Online Protection (EOP)
* **_Setting up external email warning to help users identify emails from outside the organization_**
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/emailwarn1.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/emailwarn2.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/emailwarn3.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/emailwarn4.png)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/emailwarn5.png)


## Step 3: Implementing Entra ID security features
* **_Enabling multi-factor authentication (MFA) for all users_**
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/9d917f95fc0149aa490193a574d71cc0192bdb0a/Implementing%20Phishing%20Protection%20in%20M365/email_security/mfa.png)


## Benefits
This solution provides the following benefits:

* Reduced risk of phishing attacks and compromised accounts.
* Improved email security and filtering capabilities.
* Enhanced user authentication and access controls.


# Skills
- Microsoft 365 Security and Compliance
- Microsoft Defender for Office 365
- Exchange Online Protection (EOP)
- Entra ID 
- Conditional Access 

  
## Challenges Faced
During the implementation of Microsoft 365 security and compliance solutions, I encountered two significant challenges that tested my problem-solving skills:

1. I lacked the necessary administrative permissions to configure DKIM, DMARC, and SPF for email authentication.
2. Inability to access Threat Explorer due to licensing restrictions.

This limitation prevented me from fully securing the Microsoft 365 environment and mitigating potential security threats.

## Recommendations
To overcome these challenges, I recommend the following:

- Obtain the necessary administrative permissions to configure and implement security features.
- Ensure that all configuration settings are accessible and properly configured.
- Prioritize the implementation of email authentication to prevent spoofing and Threat Explorer to enhance the organization's security posture.

By addressing these challenges, the organization can significantly improve its security posture and reduce the risk of security threats.

## Summary of Actions Taken

Feature                              |           Configuration
:-----------------------------------:|:--------------------------------------------------------------:
Defender Anti-Phishing               |Protects against impersonation & phishing attacks
Safe Links                           |Scans & blocks malicious URLs
Safe Attachments                     |Scans email attachments before delivery
External Email Warning               |Alerts users about external emails
Attack Simulation Training           |Phishing simulation for employees
Multi-Factor Authentication (MFA)    |Protects user accounts from phishing



## Conclusion
By implementing this solution, the company can significantly reduce the risk of phishing attacks and improve overall email security in M365.
