# 🤖 Pluto Daycare AI Chatbot (RAG Powered)

An AI-powered customer support chatbot built using **LangChain + OpenAI + ChromaDB** that answers user queries based on real website content from Pluto Daycare.

This project demonstrates a complete Retrieval-Augmented Generation (RAG) pipeline integrated with a Streamlit UI for interactive querying.

---

## 🚀 Project Overview

This chatbot:

✔ Scrapes website content from Pluto Daycare  
✔ Splits content into semantic chunks  
✔ Converts text into embeddings  
✔ Stores embeddings in Chroma vector database  
✔ Retrieves relevant context for user queries  
✔ Uses OpenAI LLM to generate grounded answers  
✔ Provides an interactive chat interface via Streamlit  

---

System prompt ensures:

Maximum 3 sentences

Concise answers

No hallucination

Says “I don’t know” if answer not found

pluto-daycare-chatbot/
│
├── app1.py              # Streamlit RAG chatbot
├── RAG_Chatbot.ipynb    # Experimentation & testing
├── requirements.txt
└── README.md
