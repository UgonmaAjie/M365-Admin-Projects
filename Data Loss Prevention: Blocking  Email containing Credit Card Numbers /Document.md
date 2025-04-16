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

### Step 2: Navigated to Data Loss Prevention (DLP) on M365 Compliance portal

1. Clicked on **Data Loss Prevention**
2. Clicked on **Policies**

---

### Step 3: Create a New DLP Policy

1. Clicked ** Create policy**.
2. Chose **Custom policy**
3. Click **Next**.

---

### Step 4: Name the Policy

- Name: `Block Emails with Credit Card Info`
- Description: `To block emails containing sesitive information like credit cards`
Click **Next**.

---

### Step 5: Choose Locations

- Selected **Exchange email**.
- Clicked **Next**.

---

### Step 6: Define Policy Rules

1. **Conditions**:
   - Content contains: **Credit Card Number** (predefined sensitive info type)
   - Detection threshold: **at least 1 occurrence**
2. **Actions**:
   - **Block everywhere**
   - Click **Next**.

---

### Step 7: Set Test or Enforce Mode

- Chose **Turn it on right away**
- Click **Next**.

---

### Step 8: Review and Finish

- Review all settings.
- Click **Submit** to create and activate the policy.

---

## Verification Steps

1. Sent a test email with a dummy credit card number (4111 1111 1111 1111).
2. Confirmed that:
   - The email is blocked
   - The sender received a notification
  ---
