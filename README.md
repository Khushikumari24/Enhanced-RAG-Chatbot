# 🤖 Enhanced Professional RAG Chatbot

A production-ready, Retrieval-Augmented Generation (RAG) chatbot built with LangChain, Hugging Face, and Gradio. Designed to run efficiently on both local CPUs and Google Colab T4 GPUs.

## 🚀 Features
- **Multi-Format Ingestion**: Supports PDF, DOCX, TXT, and Web URLs.
- **Hybrid Retrieval**: Combines Dense (FAISS + BGE-Large) and Sparse (BM25) search for maximum accuracy.
- **Cross-Encoder Reranking**: Two-stage retrieval pipeline for high-precision context fetching.
- **Optimized LLM**: Mistral-7B-Instruct with 4-bit quantization (BitsAndBytes) to fit in ~4.5GB VRAM.
- **Professional UI**: Interactive Gradio interface with chat history, source citations, and latency tracking.

## 🛠️ Tech Stack
- **LLM**: `mistralai/Mistral-7B-Instruct-v0.2`
- **Embeddings**: `BAAI/bge-large-en-v1.5`
- **Reranker**: `cross-encoder/ms-marco-MiniLM-L-6-v2`
- **Vector DB**: `FAISS` (Facebook AI Similarity Search)
- **Framework**: `LangChain`, `Hugging Face Transformers`, `Gradio`

## ⚙️ Local Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Enhanced-RAG-Chatbot.git
   cd Enhanced-RAG-Chatbot
