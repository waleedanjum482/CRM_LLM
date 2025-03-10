# 🚀 AI-Powered CRM Workflow with LangGraph

A multi-agent AI workflow using **LangGraph**, **Mistral-7B**, and **HubSpot API** for automated lead management and email notifications.

---

## 📌 Features

✅ **LangGraph-based Multi-Agent System**  
✅ **Uses Open-Source LLM (Mistral-7B) via Hugging Face**  
✅ **HubSpot CRM Integration** (Lead creation & management)  
✅ **SMTP Email Notifications** (Gmail, Mailgun, or any SMTP server)  
✅ **Google Colab & Local Environment Support**  

---

## 🛠️ Setup Instructions

### 1 Clone the Repository

```sh
git clone https://github.com/your-username/your-repo.git
cd your-repo

### 2 Install Requirements

pip install langchain langgraph transformers hubspot-api-client requests smtplib

### 3 Use API key for Hubspot

{
    "hubspot_api_key": "your_hubspot_api_key",
    "smtp_server": "smtp.gmail.com",
    "smtp_port": 465,
    "smtp_user": "your_email@gmail.com",
    "smtp_password": "your_email_password",
    "sender_email": "your_email@gmail.com"
}

