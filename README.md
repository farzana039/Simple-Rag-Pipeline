# Simple RAG Pipeline

This project is a beginner-friendly tutorial for building a **Retrieval Augmented Generation (RAG) system**.  
It showcases the end-to-end process of document indexing, retrieval, AI-powered response generation, and evaluation — all through a simple **command-line interface (CLI).**

## 🔹 What is RAG?
RAG (Retrieval Augmented Generation) is a framework that combines information retrieval with large language models (LLMs). It retrieves relevant content from a knowledge base and augments the model’s response with accurate, contextual information.

## 🚀 Features
- **Document Indexing** – Process and split documents (e.g., PDFs, text files) into smaller, manageable chunks.  
- **Vector Storage & Retrieval** – Store document embeddings in a **vector database (LanceDB)** and perform similarity search to retrieve relevant content.  
- **AI-Powered Response Generation** – Use the **OpenAI API** to generate concise answers grounded in the retrieved context.  
- **Response Evaluation** – Compare generated answers against expected outputs and analyze reasoning behind evaluations.  

## 🛠️ Tech Stack
- **Python** – Core language  
- **LanceDB** – Vector database for embeddings  
- **OpenAI API** – For LLM-powered response generation  
- **LangChain** – Orchestration of RAG pipeline  
- **Typer** – CLI framework  

## 🎯 Purpose
This project is designed as a **learning resource** for anyone new to Retrieval Augmented Generation.  
By exploring this repo, you will understand how to:  
1. Ingest and process documents.  
2. Create embeddings and store them in a vector DB.  
3. Query documents and augment responses with context.  
4. Evaluate and benchmark the results.  

---

