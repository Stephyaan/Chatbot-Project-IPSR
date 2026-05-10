# Chatbot-Project-IPSR

This repository contains two chatbot projects built using n8n, Pinecone, and RAG.

## Projects

### 1. IPSR Courses Assistant
A chatbot that answers user questions about IPSR courses using a vector database.

**Features**
- Course recommendations only from stored vector database
- No custom/generated course suggestions
- n8n workflow integration
- Pinecone vector storage

**Live Chatbot**
https://stephyann02.app.n8n.cloud/webhook/e248ec9b-d67b-42ba-b91c-638d14a0911c/chat

---

### 2. Union Budget Chatbot
A chatbot that answers questions strictly from the Union Budget Analysis 2025–26 document.

**Features**
- Budget-specific responses only
- No hallucinated answers
- Uses uploaded PDF knowledge base

**Live Chatbot**
https://stephyann02.app.n8n.cloud/webhook/62e2a0c5-190c-4653-ae0c-0e9e69f35275/chat

## Folder Structure
- `data/` → datasets
- `docs/` → documentation files
- `screenshots/` → workflow and Pinecone screenshots
- `workflows/` → exported n8n workflow JSON files
