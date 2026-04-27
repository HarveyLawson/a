# 📧 Email Analysis Guide

## 📌 Overview

Cyber threats have evolved significantly over time, with many attacks now originating from malicious emails targeting unsuspecting users.

---

## ✅ What this tool does

The Email Analysis feature helps mitigate these risks by:

- Connecting to an email service to scan incoming emails for threats  
- Continuously monitoring all incoming emails in real-time  
- Tagging suspicious emails and highlighting potentially dangerous links  
- Warning users when an email is identified as malicious or high-risk  

---

## 🧪 Example Threats

The mailbox includes simulated phishing emails such as:
- Phishing Attempts
- Fake login requests
- Suspicious attachments  
- Malicious links disguised as legitimate services  

---

## 🧭 Accessing the Email Analysis Page

Navigate to **"Email Analysis"** from the left sidebar of the application.

---

## ⚠️ Accessing the Email Mailbox (Important)

> 🚨 **Important:** This step is required to fully demonstrate the feature.

Use the following mailbox:

👉 **http://mail.heml.cc**

This is a **simulated mailbox environment** used for demonstration purposes.

- No login or setup is required  
- Emails are automatically generated and sent to this mailbox  
- This avoids using real email providers while still demonstrating full functionality  

> 💡 Keep this page open while using the Email Analysis feature to observe live updates.

---

## ▶️ Using Email Analysis

On the Email Analysis page, you will see system statistics followed by options to:

- Start continuous email monitoring  
- Perform a one-time scan of existing emails  

![Email Analysis Options](./images/image11.png)

---

### 🔄 Continuous Monitoring

Click **"Turn On Analysis"** to begin real-time email scanning.

![Turn On Analysis](./images/image12.png)

Once enabled:
- The system will continuously check for new emails  
- Incoming emails will be automatically analysed  

---

### 📬 Live Mailbox Updates

While monitoring is active, the mailbox will update in real-time:

- Emails will be tagged based on threat level  
- Suspicious content (e.g. links) will be highlighted  

![Mailbox Updates](./images/image13.png)

---

### ⚠️ Threat Warnings

Clicking on a **High-Risk** or **Suspicious** email will display warning messages to the user.

![Threat Warning](./images/image14.png)

---

## ✅ Expected Outcome

- Emails are analysed as they arrive  
- Threat levels are clearly indicated  
- Users are warned before interacting with potentially malicious content  

---
## 🚨 Events and Actions

At the bottom of the Email Analysis page, all detected threat events are displayed in a table.

Each event includes summary information along with two available actions:

- **View**
- **Acknowledge**

![Email Events Table](./images/image15.png)

---

### 🔍 Viewing Event Details

Click **"View"** on any threat event to open a detailed panel with more information about the detected issue.

![Email Event Details](./images/image16.png)

---

### ⚙️ Available Actions

After reviewing the event details, the following options are available:

![Email Event Actions](./images/image17.png)

- **Acknowledge**  
  Mark the event as reviewed without taking further action.

- **Delete & Block**  
  Immediately deletes the email and blocks the sender from future communication.  
  > ✅ **Recommended action**

- **Block Sender**  
  Blocks the sender from sending future emails but does not delete the existing email.

- **Mark as Safe**  
  Reclassifies the email as safe if it has been incorrectly identified (e.g. trusted sender).

---

### ✅ Event Resolution

If any action other than **Acknowledge** is selected, the event status will be updated to:

**Resolved**

![Resolved Email Event](./images/image18.png)
