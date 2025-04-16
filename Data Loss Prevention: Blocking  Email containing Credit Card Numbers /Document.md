## Data Loss Prevention (DLP): Blocking Emails Containg Credit Card Numbers

## Scenario
## A company wants to ensure sensitive information like credit card numbers is not sent through email. This solution uses Microsoft Purview's DLP capabilities to block such messages.

---

## Prerequisites

- Microsoft 365 Compliance license (E5 or equivalent)
- Global Administrator or Compliance Administrator role
- Access to Microsoft Purview Compliance Portal

---

## Step-by-Step Configuration

### Step 1: Navigated to Data Loss Prevention (DLP) on M365 Compliance portal

1. Clicked on **Data Loss Prevention**
2. Clicked on **Policies**
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/2d60929b48728e1f12ff5a81eb63c15cda28d61d/Data%20Loss%20Prevention%3A%20Blocking%20%20Email%20containing%20Credit%20Card%20Numbers%20/data%20loss%20prevention/dlp1.png)
---

### Step 2: Create a New DLP Policy

1. Clicked ** Create policy**.
2. Chose **Custom policy**
3. Click **Next**.
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/2d60929b48728e1f12ff5a81eb63c15cda28d61d/Data%20Loss%20Prevention%3A%20Blocking%20%20Email%20containing%20Credit%20Card%20Numbers%20/data%20loss%20prevention/dlp2.png)
---

### Step 3: Name the Policy

- Name: `Block Emails with Credit Card Info`
- Description: `To block emails containing sesitive information like credit cards`
Click **Next**.
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/2d60929b48728e1f12ff5a81eb63c15cda28d61d/Data%20Loss%20Prevention%3A%20Blocking%20%20Email%20containing%20Credit%20Card%20Numbers%20/data%20loss%20prevention/dlp3.png)
---

### Step 4: Choose Locations

- Selected **Exchange email**.
- Clicked **Next**.
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/2d60929b48728e1f12ff5a81eb63c15cda28d61d/Data%20Loss%20Prevention%3A%20Blocking%20%20Email%20containing%20Credit%20Card%20Numbers%20/data%20loss%20prevention/dlp4.png)
---

### Step 5: Define Policy Rules

1. **Conditions**:
   - Content contains: **Credit Card Number** (predefined sensitive info type)
   - Detection threshold: **at least 1 occurrence**
2. **Actions**:
   - **Block everywhere**
   - Click **Next**.
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/2d60929b48728e1f12ff5a81eb63c15cda28d61d/Data%20Loss%20Prevention%3A%20Blocking%20%20Email%20containing%20Credit%20Card%20Numbers%20/data%20loss%20prevention/dlp5.png)
---

### Step 6: Review and Finish

- Review all settings.
- Click **Submit** to create and activate the policy.
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/2d60929b48728e1f12ff5a81eb63c15cda28d61d/Data%20Loss%20Prevention%3A%20Blocking%20%20Email%20containing%20Credit%20Card%20Numbers%20/data%20loss%20prevention/dlp6.png)
---

## Verification Steps

1. Sent a test email with a dummy credit card number (4111 1111 1111 1111).
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/2d60929b48728e1f12ff5a81eb63c15cda28d61d/Data%20Loss%20Prevention%3A%20Blocking%20%20Email%20containing%20Credit%20Card%20Numbers%20/data%20loss%20prevention/dlp7.png)

2. Confirmed that:
   - The email is blocked
   - The sender received a notification
![](https://github.com/UgonmaAjie/M365-Admin-Projects/blob/2d60929b48728e1f12ff5a81eb63c15cda28d61d/Data%20Loss%20Prevention%3A%20Blocking%20%20Email%20containing%20Credit%20Card%20Numbers%20/data%20loss%20prevention/dlp8.png)
  ---
