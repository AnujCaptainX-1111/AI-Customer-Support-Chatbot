# 🤖 AI Customer Support Chatbot

An AI-powered Customer Support Chatbot built using **n8n, Google Sheets, and OpenRouter AI**. This project automates customer support by answering customer queries using a predefined FAQ knowledge base.

## 🚀 Project Overview

The AI Customer Support Chatbot helps customers get quick answers to frequently asked questions related to orders, payments, returns, delivery, and customer support.

It uses an automated n8n workflow to retrieve FAQ data from Google Sheets and generate relevant responses using an AI language model.

## ✨ Features

- 💬 Interactive AI-powered customer chat
- 📊 Google Sheets FAQ database integration
- 🤖 AI-generated customer responses
- ⚡ Automated workflow using n8n
- 🔗 OpenRouter AI model integration
- 📦 FAQ data aggregation
- 🌐 Hosted chat interface
- 🛠️ Easy-to-update knowledge base

## 🧰 Technologies Used

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| Google Sheets | FAQ knowledge base |
| OpenRouter AI | AI language model |
| GPT-4.1-mini | Chat model |
| JSON | Workflow configuration |
| Excel (.xlsx) | FAQ database backup |

## 🔄 Workflow Architecture

The project follows this workflow:

1. **When Chat Message Received:** Receives the customer's question.
2. **Google Sheets:** Fetches FAQ records from the knowledge base.
3. **Aggregate:** Combines FAQ records into a single list.
4. **Basic LLM Chain:** Processes the customer's question with FAQ context.
5. **OpenRouter Chat Model:** Generates the final AI response.

## 📂 Project Structure

```text
AI-Customer-Support-Chatbot/
│
├── AI Customer Support Chatbot.json
│
├── Customer Support Knowledge Base.xlsx
│
├── AI_Customer_Support_Chatbot_Workflow_Presentation.pptx
│
└── README.md
```

## ⚙️ Setup Instructions

### Step 1: Download the Project
Clone or download this GitHub repository.

### Step 2: Import Workflow
- Open your n8n account.
- Create a new workflow.
- Import the downloaded JSON workflow.

### Step 3: Connect Google Sheets
- Connect your Google account.
- Select your FAQ spreadsheet.
- Verify the Category, Question, and Answer columns.

### Step 4: Configure OpenRouter
- Create or connect your OpenRouter API credentials.
- Select the required chat model.
- Configure the Basic LLM Chain.

### Step 5: Test the Chatbot
- Execute the workflow.
- Open the hosted chat interface.
- Ask questions about orders, payments, returns, or delivery.

## 💡 Example Questions

- How can I track my order?
- What is the payment method?
- What is your return policy?
- What is the delivery time?
- How can I contact customer support?

## 🎯 Project Objective

The main objective of this project is to automate customer support operations, reduce manual effort, and provide quick responses to frequently asked customer questions.

## 🔮 Future Improvements

- Add multilingual customer support.
- Integrate order tracking APIs.
- Add customer conversation history.
- Improve chatbot response accuracy.
- Add analytics and reporting dashboard.

## 👨‍💻 Author

**AnujCaptainX-1111**

GitHub: [Visit My GitHub Profile](https://github.com/AnujCaptainX-1111)

---

⭐ If you find this project useful, consider giving this repository a Star!

**Thank you for visiting my project!**
