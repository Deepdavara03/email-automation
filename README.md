# Email-automation
# 🤖 AI Email Follow-Up Automation

An AI-powered email automation workflow built with **n8n** that automates lead follow-ups, personalized email generation, email validation, delivery, and tracking.

The workflow reads lead information from Google Sheets, uses AI agents powered by Google Gemini to generate personalized email content, validates recipient email addresses, sends emails through SMTP, and updates the lead status automatically.

---

## 🚀 Features

- 🤖 AI-powered personalized email generation
- 📊 Google Sheets integration for lead management
- 🧠 Google Gemini AI integration
- 📧 Automated SMTP email sending
- ✅ Email address validation
- ⏰ Scheduled workflow execution
- 🔄 Automated follow-up processing
- 🔀 Conditional routing based on lead data
- ⏳ Wait and delay handling
- 📋 Automatic email status tracking
- 🔁 Batch/loop processing for multiple leads
- 🏢 Industry-specific email generation
- 📝 Automatic update of sent status and email content

---

## 🧠 How It Works

The automation follows this general pipeline:

```text
Google Sheets
     ↓
Read Lead Data
     ↓
Validate / Filter Lead
     ↓
Select Email Campaign
     ↓
Google Gemini AI Agent
     ↓
Generate Personalized Email
     ↓
Validate Email Address
     ↓
Send Email via SMTP
     ↓
Update Google Sheets
     ↓
Track Email Status
