## Implementing Email Encryption for Sensitive Documents Using Microsoft 365.

## Overview
A law firm wants to ensure that emails containing sensitive legal documents are encrypted when sent externally.

## Requirements
* Encrypt emails containing sensitive legal documents
* Ensure encryption is applied when sending emails externally
* Use Microsoft 365 (M365) to implement the solution

## Solution
1. Created a Mail Flow rule to detect and encrypt sensitive emails

## Implementation Steps
### Step 1: Created a Mail Flow Rule
* Went to the Microsoft 365 Exchange Admin Center
* Navigated to Mail flow > Rules
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/main/Email%20Encryption%20for%20Sensitive%20Documents/email_encryption/rule1.jpg)
---
* Created a new rule to detect and encrypt sensitive emails
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/main/Email%20Encryption%20for%20Sensitive%20Documents/email_encryption/rule2.jpg)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/main/Email%20Encryption%20for%20Sensitive%20Documents/email_encryption/rule3.jpg)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/main/Email%20Encryption%20for%20Sensitive%20Documents/email_encryption/rule4.jpg)
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/main/Email%20Encryption%20for%20Sensitive%20Documents/email_encryption/rule5.jpg)
---
### Step 2
* Successfully tested the solution to ensure emails containing sensitive legal message are encrypted when sent externally
### Sent an encrypted email to a recipient and verified that they could access the email and its contents and was prompted to authenticate before accessing the email contents
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/main/Email%20Encryption%20for%20Sensitive%20Documents/email_encryption/test1.jpg)
---
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/main/Email%20Encryption%20for%20Sensitive%20Documents/email_encryption/test2.jpg)

* Confirmed that the recipient was able to access the email contents after authenticating
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/main/Email%20Encryption%20for%20Sensitive%20Documents/email_encryption/test3.jpg)

## Challlenge Faced
During the implementation of email encryption using Microsoft 365, the notable challenge I faced was:
Inability to carry out Office 365 Message Encryption (OME) on Microsoft Purview, the reason due to insufficient permissions.
