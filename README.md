 WhatsApp AI Expense Tracker (n8n + AI Automation)

An AI-powered automation system that tracks expenses directly from WhatsApp messages using n8n workflows, AI-based text parsing, Google Sheets, and Twilio.

--Features
WhatsApp message input via Twilio webhook
AI extracts structured expense data from Hinglish text
Auto stores transactions in Google Sheets
Sends instant WhatsApp confirmation message
Fully automated no-code/low-code workflow using n8n

🧠 How it works
User sends WhatsApp message
Example:
parantha 120 rupees
n8n Webhook receives message
AI Agent extracts:
{
  "amount": 120,
  "category": "food",
  "item": "parantha",
  "type": "expense",
  "people": ""
}
Data stored in Google Sheets
Confirmation sent back on WhatsApp

Tech Stack
n8n (Automation)
Twilio WhatsApp API
Google Sheets API
AI Agent (LLM-based extraction)
JavaScript (data transformation)
Workflow Preview

(Add screenshot of your n8n workflow here)
<img width="1521" height="637" alt="Screenshot 2026-06-24 180839" src="https://github.com/user-attachments/assets/4e769ddc-3e7a-4997-bf2c-bc03ab406f1b" />


Setup
Import workflow in n8n
Configure Twilio WhatsApp webhook
Connect Google Sheets
Add AI Agent credentials
Activate workflow

Example Messages
"chai 40 rupaye"
"zomato dinner 300"
"salary received 25000"
📌 Use Case

Personal finance tracking via WhatsApp using AI automation.

👩‍💻 Author

Samridhi Sharma
AI & ML Engineer | Automation Builder | CSE Student
