# 🤖 n8n Feedback Form Automation

This project is an AI-powered feedback automation workflow built using n8n.

## 🚀 What it does

- Captures form submissions
- Processes data using AI (Google Gemini)
- Stores responses in Airtable
- Sends automated email responses

## 🧩 Workflow Overview

1. Form submission trigger
2. AI agent processes feedback
3. Data is merged and routed using Switch
4. Records stored in Airtable
5. Email sent via Gmail

## 🛠 Tech Stack

- n8n (workflow automation)
- Google Gemini API (AI processing)
- Airtable (database)
- Gmail API (email automation)

## 📂 Files

- `workflow.json` → Exported n8n workflow

## ⚙️ How to Use

1. Import `workflow.json` into n8n
2. Configure credentials:
   - Airtable
   - Gmail
   - Gemini API
3. Run the workflow

## 💡 Use Case

Automates customer feedback handling and response generation using AI.

## 📌 Author

Tanishq Badkul
