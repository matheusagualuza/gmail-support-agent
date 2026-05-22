Gmail Support Agent — Hashtag Treinamentos
AI-powered email support agent built with n8n, Google Gemini, and Gmail.
What it does
Automatically handles customer support emails for an online course platform. The agent reads incoming emails, identifies whether the sender is a customer or internal staff, and responds with context-aware answers — no human needed for routine questions.
How it works

Gmail Trigger monitors incoming emails in real time
Conditional check identifies if the email contains "Hashtag" in the sender — separating staff from customers
If customer: AI Agent (powered by Google Gemini) reads the email, recalls conversation history via Simple Memory, and drafts a personalized response based on course information
Reply is sent automatically back to the customer via Gmail

Stack
n8n, Google Gemini, Gmail API, Simple Memory
