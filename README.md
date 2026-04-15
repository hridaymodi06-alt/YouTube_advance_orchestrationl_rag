# YouTube_advance_orchestrationl_rag
# 🎥 AI Video Understanding System (Advanced RAG + Agent Orchestration)

## 🚀 Overview
This project is an advanced AI system that transforms long-form YouTube videos into structured, searchable knowledge. It combines Retrieval-Augmented Generation (RAG) with agent-based orchestration to provide accurate, context-aware answers from video content.

Unlike basic RAG systems, this project implements dynamic query routing, context selection, and conversational memory using a state-driven architecture.

---

## 🧠 Key Features

- 🔍 **RAG Pipeline**
  - Transcript ingestion → chunking → embeddings → FAISS vector search
  - Semantic retrieval with context-aware responses

- 🤖 **Agent-Based Workflow (LangGraph)**
  - State-driven pipeline
  - Dynamic decision making for query handling

- ⚡ **Smart Query Routing**
  - Automatically decides:
    - Top-K retrieval (for specific queries)
    - Full-context reasoning (for broader queries)

- 🧩 **Multi-LLM Integration**
  - Uses different models (Groq, Gemini) for:
    - reasoning
    - summarization
    - response generation

- 🧠 **Conversational Memory**
  - Maintains history-aware responses
  - Handles follow-up queries intelligently

- 📊 **Structured Output Generation**
  - Timeline-based summaries
  - Compressed knowledge blocks

- 🔗 **Context Expansion Logic**
  - Groups adjacent relevant chunks
  - Improves coherence of retrieved information

---

## 🏗️ Architecture
