
# email-summary-n8n-workflow
An n8n workflow that summarizes incoming emails with AI, saves them to Google Sheets, and sends a Telegram notification.
# 📧 AI-Powered Email Summarizer Workflow (n8n)
## 📌 Overview
This project is an **n8n automation workflow** that:
1. Triggers when a new email is received.
2. Extracts key information from the email (sender name, sender email, and message body).
3. Uses an **AI model** to generate a short summary of the email.
4. Saves the summary into a **Google Sheet** for record keeping.
5. Sends a **Telegram notification** with the summary.

---

## 🚀 Workflow Steps
1. **Email Trigger** – Listens for new incoming emails.
2. **Extract Email Info** – Gets sender details and email content.
3. **AI Summarization** – Summarizes the email text using an AI node.
4. **Save to Google Sheet** – Logs summarized data in a Google Sheet.
5. **Telegram Notification** – Sends a message with the summary.

---

## 🛠️ Requirements
- **n8n** installed locally or hosted.
- Email credentials (IMAP/SMTP).
- AI integration (e.g., Grok AI, OpenAI, etc.).
- Google Sheets API access.
- Telegram Bot API Token and Chat ID.

---

## 📷 Workflow Preview
<img  center width="841" height="380" alt="image" src="https://github.com/user-attachments/assets/7d2ca2c4-922f-4481-92ee-8c2cb978a908" />

---

## 📥 How to Import
1. Download the `email_summary_workflow.json` file from this repo.
2. Open n8n and click **Import**.
3. Select the downloaded file and click **Import Workflow**.
4. Update credentials for:
   - Email node
   - AI node
   - Google Sheets node
   - Telegram node

---

## 📄 License
This project is open-source under the **MIT License**.
### Nasir Sharif 

---
💡 *Created with n8n – Automate everything without coding!*

