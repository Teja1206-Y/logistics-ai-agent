# 🚚 Logistics AI Agent

Agentic AI system for logistics operations built with LangChain, FAISS, Groq LLaMA, FastAPI, and React.

## 🏗️ Architecture
User Query → React Frontend → FastAPI Backend → LangChain Agent → Tools (RAG + Status Analyzer) → Groq LLaMA → Response

## ⚡ Tech Stack
- **LLM:** Groq LLaMA 3.3 70B
- **Agent Framework:** LangChain ReAct Agent
- **Vector Store:** FAISS
- **Embeddings:** HuggingFace MiniLM
- **Backend:** FastAPI
- **Frontend:** React + Vite

## 🛠️ Features
- Agentic reasoning with Thought → Action → Observation loop
- RAG pipeline over logistics knowledge base
- Shipment status analysis and workflow automation
- NDR workflow, SLA breach detection, delay RCA
- Conversational memory across sessions

## 🚀 Setup
```bash
pip install -r requirements.txt
uvicorn app:app --no-reload
cd frontend && npm install && npm run dev
```

