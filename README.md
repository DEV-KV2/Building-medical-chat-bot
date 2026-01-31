# Building-medical-chat-bot

# 🏥 Medical Chatbot (RAG-based)

A Retrieval-Augmented Generation (RAG) based **Medical Chatbot** built using:
- Flask
- LangChain
- Groq LLM
- Pinecone Vector Database
- HuggingFace Embeddings

---

## 🚀 Features
- Medical question answering
- Context-aware responses using Pinecone
- Groq LLM (OpenAI-compatible, fast & free-tier friendly)
- Secure API key handling using environment variables

---

## 🛠 Tech Stack
- Python
- Flask
- LangChain
- Groq API
- Pinecone
- HuggingFace Embeddings

---

## 📂 Project Structure
Building-medical-chat-bot/
│
├── app.py
├── store_index.py
├── src/
│ ├── helper.py
│ └── prompt.py
│
├── templates/
│ └── index.html
│
├── README.md
└── .gitignore


---

## 🔐 Environment Variables
Set the following **environment variables** (DO NOT hardcode):
GROQ_API_KEY=your_groq_api_key
PINECONE_API_KEY=your_pinecone_api_key

setx GROQ_API_KEY "your_key"
setx PINECONE_API_KEY "your_key"

Run the Application
python app.py

Open in browser:

http://localhost:8080
