# 🧠 RAG with LangChain, Hugging Face & OpenAI | Google Colab

This project demonstrates how to build a **Retrieval-Augmented Generation (RAG)** system using:

- 🌐 **LangChain** for document loading and chaining
- 🔍 **FAISS** for vector search
- 🤗 **Hugging Face Transformers** for the LLM
- 🧠 **OpenAI Embeddings** for encoding text
- ☁️ **Google Colab** for execution

---

## 🚀 Features

- Fetches and splits web content (e.g., LangSmith docs)
- Converts text chunks into embeddings using OpenAI
- Stores and searches chunks using FAISS vector store
- Uses Hugging Face LLMs to answer questions using retrieved context

---

## 📚 Workflow Overview

1. **Data Loading & Preprocessing**
   - Load website data using LangChain
   - Split content into manageable chunks

2. **Vectorization**
   - Generate embeddings with OpenAI
   - Store chunks in a FAISS vector database

3. **RAG Pipeline**
   - Retrieve relevant chunks for a query
   - Use a Hugging Face model to answer using context

4. **User Interaction**
   - Ask a question
   - Retrieve & respond using LLM + relevant context

---

## 🔧 Installation (on Google Colab)

Paste the following in your Colab notebook:

```bash
!pip install langchain openai huggingface_hub faiss-cpu
