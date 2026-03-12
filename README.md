# n8n-AI-ChatBot-Project
AI FAQ chatbot using n8n automation, Groq LLM, and Google Sheets.

# 🤖 AI Customer Support Bot (n8n + Groq + Google Sheets)

An AI-powered customer support chatbot built using **n8n automation**, **Groq LLM**, and **Google Sheets FAQ database**.

This bot reads FAQ data from Google Sheets and answers user questions using an AI model.

---

## 🚀 Features

* AI-powered chatbot
* FAQ knowledge base from Google Sheets
* Webhook chat interface
* Natural language answers
* Easy to expand with more FAQs

---

## 🧠 Architecture

User Question
⬇
n8n Chat Trigger / Webhook
⬇
Google Sheets (FAQ Database)
⬇
Groq LLM (Llama 3.1)
⬇
AI Response returned to user

---

## 📂 Project Structure

```
n8n-ai-customer-support-bot
│
├── workflow/
│   └── ai-customer-support-workflow.json
│
├── screenshots/
│   └── chatbot-demo.png
│
├── README.md
└── LICENSE
```

---

## ⚙️ Setup Instructions

### 1️⃣ Install n8n

Install n8n locally or use n8n cloud.

https://n8n.io/

---

### 2️⃣ Import Workflow

Open n8n and import:

```
workflow/ai-customer-support-workflow.json
```

---

### 3️⃣ Add Credentials

Configure:

* Google Sheets API
* Groq API Key

---

### 4️⃣ Run Workflow

Start the workflow and test using the webhook chat interface.

---

## 💬 Example Questions

Try asking:

* What are your working hours?
* What is your refund policy?
* How can I contact support?

---

## 🛠 Tech Stack

* n8n
* Groq LLM (Llama 3.1)
* Google Sheets
* Webhooks
* JavaScript

---

## 📈 Future Improvements

* Vector search FAQ
* Conversation memory
* WhatsApp chatbot integration
* Telegram bot integration
* Dashboard for FAQs

---

## 👨‍💻 Author

Built as an automation + AI project using n8n.

---


