#  I Ethics RAG Chatbot (Flowise)

## Project Overview
This project is a **Retrieval-Augmented Generation (RAG) Chatbot** built using **Flowise**.  
It allows users to upload documents and ask questions, with the chatbot generating accurate, context-based answers using retrieved data instead of relying only on pre-trained knowledge.

---

## Features
- Document-based question answering  
- Context-aware responses using RAG  
- Reduced hallucinations  
- Supports AI ethics (transparency & reliability)  
- API integration for real-time interaction  

---

## Architecture
The system follows a RAG pipeline:

1. **Document Upload**
2. **Text Embedding (Google Gemini Embeddings)**
3. **Vector Database Storage**
4. **Retriever fetches relevant data**
5. **LLM generates final response**

---

## Tech Stack
- Flowise  
- Google Gemini Embeddings  
- Large Language Model (LLM)  
- Vector Database  
- Node.js (API integration)

---

## Project Workflow
<img width="1788" height="831" alt="image" src="https://github.com/user-attachments/assets/752a9552-6c0f-4d3f-ba67-50f793c35c75" />
