# 🛵 Mrsool Chatbot Support

An AI-powered customer service chatbot for Mrsool, built using Node.js, Express, and **Meta’s LLaMA 3 LLM**. The chatbot can:

- Guide customers on how to place an order
- Track order status using order ID
- Cancel orders on request
- Automatically respond in Arabic or English depending on the customer's language

---

## 🚀 Features

✅ Intelligent replies powered by **LLaMA 3** via function-calling  
✅ Language detection (Arabic / English)  
✅ Function calling to:  
  - Lookup order  
  - Cancel order  
✅ Reads and updates order info from a local JSON file  
✅ Frontend-ready: works with React frontend or any RESTful clients  

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express  
- **AI**: LLaMA 3 (Meta) + Custom Function Calling  
- **Data Storage**: JSON file (mock dataset)  
- **Environment**: dotenv for secrets  
- **Deployment-ready**: can be hosted on Vercel, Heroku, etc.  

---

## 📁 Project Structure
mrsool-chatbot/
├── orders.json # Mock order database
├── .env # API keys and environment variables
├── server.js # Express server and chatbot logic
├── client/ # React frontend (optional)
└── README.md # Project documentation

---

## ✨ About the Developer

**Rawan Aldosari**  
Generative AI Engineer & LLM Developer

---


