# Squeezy
AI-driven knowledge management SaaS that lets users upload documents or websites, automatically indexes them with embeddings, and enables natural-language Q&amp;A over their private data using Retrieval-Augmented Generation (RAG).



# 🧠 AI Knowledge Platform (RAG + SaaS Dashboard)

An **AI-powered knowledge management platform** where users can upload PDFs, Word documents, or website links — the system automatically indexes their content using vector embeddings and allows **chat-based retrieval (RAG)** through a clean SaaS dashboard.

This project demonstrates **full-stack + AI integration**, **retrieval-augmented generation**, **auth + billing**, and **real deployment** — the same stack used in most modern AI startups.

---

## 🚀 Tech Stack

### Frontend
- **Next.js 14 (App Router)**
- **Tailwind CSS + shadcn/ui**
- **React Query** for data fetching
- **NextAuth.js** for authentication
- **Stripe** for billing (planned)

### Backend
- **FastAPI** for REST API
- **PostgreSQL** for relational data
- **Pinecone / Weaviate** for vector storage
- **Celery / Redis** for background ingestion jobs
- **LangChain / LlamaIndex** for RAG pipeline
- **OpenAI** or local LLM API for generation

### Infrastructure
- **Docker Compose** for local development
- **Vercel** (frontend) + **Render/Fly.io/AWS ECS** (backend)
- **S3 / Cloud Storage** for file uploads

---

## 🧩 Core Features

- 📄 Upload PDFs, Docs, or website URLs  
- 🔍 Automatic text extraction + chunking + embedding  
- 💬 Ask questions and get **accurate, cited answers**  
- 🧱 Multi-space organization (each project = private index)  
- 🔐 Auth, quotas, and Stripe-based subscription model  
- 📊 Usage tracking + admin analytics (planned)  

---

## 🧰 Project Structure

