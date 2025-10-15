# 💬 n8n AI Quote Agent

This repository contains an **n8n AI Agent** that generates an inspiring quote with its author using **Google Gemini** and sends it directly to your **email** each time you execute the workflow.

---

## 🧠 Features
- Uses **Google Gemini Chat Model** for quote generation.
- Includes a **Simple Memory** node for contextual replies.
- Automatically **sends the quote + author via email**.
- Fully built inside **n8n Cloud**.

---

## ⚙️ Setup Instructions

### 1️⃣ Export & Import
- Download `ai_quote_agent_workflow.json`.
- In your n8n dashboard, click **Import → From file**, and upload this JSON.

### 2️⃣ Configure Environment Variables
Copy `.env.example` to `.env` and add your keys:
```bash
GOOGLE_GEMINI_API_KEY=your_actual_key
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_password
3️⃣ Execute the Workflow
Click Execute Workflow — you’ll receive a quote in your inbox 🎉

📸 Workflow Preview

🧰 Built With
n8n

Google Gemini Chat Model

SMTP Email Node
