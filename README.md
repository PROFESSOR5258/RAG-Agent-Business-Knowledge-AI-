# RAG-Based Enterprise Knowledge Agent (n8n + Pinecone)

## 🚀 Overview
This project is a **Retrieval-Augmented Generation (RAG) agent** built using **n8n, OpenAI, and Pinecone**, designed to answer questions strictly based on uploaded business documents.

The agent **does not hallucinate** and responds only with information retrieved from approved sources.

---

## 🎯 Key Features
- Document ingestion via form upload
- Chunking with metadata tagging
- Vector storage using Pinecone
- Retrieval-as-tool architecture
- Context-aware AI responses
- Safe fallback when data is missing
- Multi-document knowledge base support

---

## 🧠 How It Works
1. User uploads business documents (PDFs)
2. Documents are chunked & embedded
3. Embeddings are stored in Pinecone
4. User asks a question via chat
5. AI retrieves relevant document chunks
6. Final answer is generated using retrieved data only

---

## 🛠 Tech Stack
- n8n
- OpenAI (GPT-4o-mini)
- Pinecone Vector Database
- LangChain Agents
- OpenAI Embeddings

---

## 💼 Use Cases
- Internal company knowledge base
- Legal & compliance document querying
- HR policies & SOP retrieval
- Customer support documentation
- Founder & ops knowledge systems

---

## 🔒 Safety & Accuracy
- Retrieval-first architecture
- Metadata-based filtering
- Explicit “not found” responses
- No free-form hallucinated answers

---

## 📈 Business Impact
- Saves time searching documents
- Improves decision accuracy
- Centralizes business knowledge
- Reduces dependency on manual lookup

---

## 📌 Status
Production-ready • Hallucination-safe • Enterprise-focused
