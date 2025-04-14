# Microsoft 365 Shared Mailbox Setup for Customer Service Team

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

## Step 1: Created a Shared Mailbox

1. Logged in to [Microsoft 365 Admin Center](https://admin.microsoft.com)
2. Navigate to **Recipients** → **Mailboxes**
3. Click **Add a shared mailbox**
4. Enter:
- **Name**: Support
- **Email**: `support@valscloud.co.uk`
5. Click **Create**

### *_Note: The steps outlined are demonstrated in the video_*
[![Creation of Shared Mailbox](https://cdn.pixabay.com/photo/2018/08/10/15/39/email-3597088_1280.jpg)](https://youtu.be/IAVqTLHW-fo)
---

## Step 2: Assign Members and Permissions

After creating the shared mailbox:

#### ✔️ Full Access (Read, and delete emails)
- Click the mailbox → **Edit members**
- Add the customer service agents

#### ✔️ Send As (Send email as `support@`)
- Scroll to **Mailbox delegation** → **Send As**
- Add the users

#### ✔️ Send on Behalf (Shows "User on behalf of support@")
- Under **Mailbox delegation** → **Send on behalf**
- Add the users

### *_Note: The steps outlined are demonstrated in the video_* 
[![Dlelegation of Shared Mailbox](https://cdn.pixabay.com/photo/2017/11/17/09/37/finger-2956974_1280.jpg)](https://youtu.be/bF3IkKXMFG8)

## 🧪 Testing & Validation

### Test 1: Full Access Permission

- Logged-in as a user with access
- Clicked user icon → **Open another mailbox**
- Type: `support@valscloud.co.uk`

### *_Note: The video includes a demonstraton on how to open and test a shared mailbox_*
[![Demo on opening a shared Mailbox](https://cdn.pixabay.com/photo/2019/02/13/10/00/contact-3994018_960_720.jpg)](https://youtu.be/_hiVYzky8hU)
---

### Test 2: Send As 

- Composed a new message
- Clicked **From** → Choose `support@valcloud.co.uk`
- Sent to a test recipient
**Expected Result:**  
Recipient sees: `From: support@valscloud.co.uk`

### *_Note: The video includes a demonstraton on how to send a mail using Send AS permission_*
[![Demo on Send As](https://cdn.pixabay.com/photo/2018/11/28/04/17/mail-3842930_1280.jpg)](https://youtu.be/Zx-VvbDpoP8)
---

### Test 3: Send on Behalf

- Composed new email
- Chose `support@valscloud.co.uk` as **From**
- Send message

**Expected Result:**  
Recipient sees: `From: user on behalf of support@valscloud.co.uk`

### *_Note: The video includes a demonstraton on how to open and test a shared mailbox_*
[![Demo on send on behalf](https://cdn.pixabay.com/photo/2020/05/30/10/09/mail-5238394_960_720.jpg)](https://youtu.be/Azkl-jFLGr4)
---


## 📊 Reporting & Monitoring

### 🔸 Using Microsoft 365 Admin Center
- Navigated to **Reports** → **Usage**
- Under **Email activity**, view send/receive logs
- Export reports as needed

### *_Note: The video includes a demonstraton on how to open and test a shared mailbox_*
[![Demo on reporting email usage](https://cdn.pixabay.com/photo/2017/10/17/14/10/financial-2860753_960_720.jpg)](https://youtu.be/20fCMIeHpj4)
---

##  Summary of Permissions

| Permission | What it Allows | Where to Set |
|------------|----------------|--------------|
| Full Access | Open, read, and delete emails | Members section |
| Send As | Send email as the shared mailbox | Mailbox Delegation → Send As |
| Send on Behalf | Send email on behalf of shared mailbox | Mailbox Delegation → Send on behalf |

---


