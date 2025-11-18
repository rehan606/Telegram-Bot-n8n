# 📌 Telegram-Bot-n8n  

**Bot Name** : RehanChat

A professional and friendly AI-powered Telegram chatbot, Name **RehanChat**, was built using **n8n**  automation workflows, **OpenAI** AI models, and **Telegram Bot API**.
The bot is designed to interact with users in a professional and friendly manner, providing helpful responses in both Bangla and English. It can understand and respond to **text messages**, provides multi-language responses, and includes personalized system logic powered by Web Developer **Rehan**.

---
### ✔️ Live Chat with Rehan Chat Bot
<a href="https://t.me/RehanChatBot"> RehanChat Bot </a>
---


## Project Image
<a href="https://ibb.co.com/VcfH8XkG"><img src="https://i.ibb.co.com/wF5J1D2q/image.png" alt="image" border="0"></a>

## 🚀 Features

### ✔️ AI-Powered Conversations  
Generates intelligent and contextual responses using OpenAI Chat models.

### ✔️ Voice Message Support  
Converts Telegram voice messages into text via **OpenAI Whisper**, then replies normally.

### ✔️ Multi-Language Support (Bangla + English)  
- Automatically detects the user’s language  
- Replies in Bangla, English, or mixed tone accordingly  

### ✔️ Professional + Friendly Tone  
Provides clean, polite, helpful responses suitable for real users or customer support.

### ✔️ Custom System Behavior  
- Includes personalized system rules to handle greetings, creator info, and contact information professionally.
- Sends **“Assalamu Alaikum! How may I assist you today?”** only at the start of a conversation
- Shares developer info when asked  
- Provides developer contact number upon request  
- Describes developer skills in a professional way  

### ✔️ Safe & Responsible  
Avoids political, harmful, explicit, illegal, medical, or unsafe content.

---

## 🧠 Tech Stack

| Component | Technology |
|----------|------------|
| Workflow Automation | n8n |
| AI Text Generation | OpenAI Chat Models |
| Speech-to-Text | OpenAI Whisper |
| Messaging Platform | Telegram Bot API |
| Hosting | n8n Cloud / Self-hosted |

---
```
## 🗂️ Project Structure

Telegram-Bot-n8n/
│
├── telegram-bot-workflow.json
├── README.md
└── assets/ (optional)

```

---

## 🔧 How It Works

### 1️⃣ Telegram Trigger  
Receives text or voice messages from Telegram users.

### 2️⃣ Voice-to-Text (If voice received)  
Voice file → **OpenAI Whisper** → Extracted text.

### 3️⃣ AI Agent Processing  
Extracted or typed user text is processed using the OpenAI Chat model with custom system instructions.

### 4️⃣ Response Delivery  
The bot sends a structured, professional reply back to the Telegram user.

---

## 🛠️ Setup & Installation

### **Prerequisites**
- n8n account / self-hosted instance  
- Telegram Bot Token (via BotFather)  
- OpenAI API Key  

---

### **Step 1: Import Workflow**
1. Export or download the workflow JSON.  
2. Open n8n → **Import Workflow**.  
3. Upload the JSON file.

---

### **Step 2: Configure Credentials**

#### **Telegram**
- Add Telegram Bot API token in n8n Credentials.

#### **OpenAI**
- Add OpenAI API key to enable:  
  - Chat model  
  - Whisper speech-to-text

---

### **Step 3: Activate the Workflow**
Activate the workflow and begin chatting with your Telegram bot.

---

## 📱 Bot Behavior Summary

- Sends greeting once:  
  **“Assalamu Alaikum! How may I assist you today?”**
- If asked: *“Who created you?”*  
  - **Bangla:** “Amake Web Developer Rehan baniyechen.”  
  - **English:** “Web Developer Rehan created me.”
- If asked for Rehan’s contact:  
  **01822-182207**
- If asked about Rehan:  
  Gives a professional summary of his skills (web development, e-commerce, automation, front-end, etc.)

---

## 📄 License  
This project is available for personal and educational use.  
Feel free to modify and improve.

---

## 👤 Developer  
**Web Developer Rehan**  
Expert in full-stack web development, e-commerce websites, front-end solutions, and automation workflows.  
📞 Contact: **01822-182207**

---

## ⭐ Contributions  
Pull requests are welcome!  
For feature requests or issues, feel free to open a GitHub issue.


