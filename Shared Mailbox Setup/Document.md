# 📬 Microsoft 365 Shared Mailbox Setup for Customer Service Team

This repository documents the **step-by-step setup, configuration, and testing** of a Microsoft 365 Shared Mailbox for a **Customer Service Team**, 
designed to efficiently handle incoming support inquiries and allow multiple team members to collaborate on email communication.

---

##  Scenario Overview

The **Customer Service Team** requires a shared mailbox to:

- 📥 Handle incoming customer emails centrally
- 👥 Allow multiple agents to access and respond to messages
- ✉️ Send emails **as** the support mailbox or **on behalf of** it
- 🧪 Perform testing to verify setup and permission accuracy

---

##  Objectives

- ✅ Create a Shared Mailbox in Microsoft 365 Admin Center
- ✅ Assign members with **Full Access**, **Send As**, and **Send on Behalf** permissions
- ✅ Test the mailbox functionality using **Outlook Web App**
- ✅ Monitor mailbox activity and usage reports via **Microsoft 365 Admin Center** 
- ✅ Record a **video demonstration** of the entire process

---

##  Tools Used

| Tool | Purpose |
|------|---------|
| Microsoft 365 Admin Center | Create and configure shared mailbox |
| Outlook Web App (OWA) | Test access and sending behavior |
| Microsoft 365 Reports | Monitor mailbox usage stats |
| Screen Recorder | Record walkthrough demo |

---

##  Setup Process 

### Step 1: Created a Shared Mailbox

1. Logged in to [Microsoft 365 Admin Center](https://admin.microsoft.com)
2. Navigate to **Recipients** → **Mailboxes**
3. Click **Add a shared mailbox**
4. Enter:
   - **Name**: Support
   - **Email**: `support@yourdomain.com`
5. Click **Create**

### *_Note: The steps outlined are demonstrated in the video_*
[![Alt text](Image Link)](Video Link)
---

### Step 2: Assign Members and Permissions

After creating the shared mailbox:

#### ✔️ Full Access (Read, and delete emails)
- Click the mailbox → **Edit members**
- Add the customer service agents (e.g., Jane, John)

#### ✔️ Send As (Send email as `support@`)
- Scroll to **Mailbox delegation** → **Send As**
- Add the users

#### ✔️ Send on Behalf (Shows "User on behalf of support@")
- Under **Mailbox delegation** → **Send on behalf**
- Add the same users

### *_Note: The steps outlined are demonstrated in the video_* (⏳ Note: (Permission propagation may take up to 60 minutes)
---

## 🧪 Testing & Validation

### ✅ Test 1: Open Shared Mailbox in Outlook

- Logged-in as a user with access
- Clicked user icon → **Open another mailbox**
- Type: `support@valscloud.co.uk`

---

### ✅ Test 2: Send As the Shared Mailbox

- Composed a new message
- Clicked **From** → Choose `support@yourdomain.com`
- Sent to a test recipient
**Expected Result:**  
Recipient sees: `From: support@valscloud.co.uk`
---

### ✅ Test 3: Send on Behalf

- Composed new email
- Chose `support@yourdomain.com` as **From**
- Send message

**Expected Result:**  
Recipient sees: `From: user@yourdomain.com on behalf of support@yourdomain.com`

---


## 📊 Reporting & Monitoring

### 🔸 Using Microsoft 365 Admin Center
- Navigated to **Reports** → **Usage**
- Under **Email activity**, view send/receive logs
- Export reports as needed

---

##  Summary of Permissions

| Permission | What it Allows | Where to Set |
|------------|----------------|--------------|
| Full Access | Open, read, and delete emails | Members section |
| Send As | Send email as the shared mailbox | Mailbox Delegation → Send As |
| Send on Behalf | Send email on behalf of shared mailbox | Mailbox Delegation → Send on behalf |

---


