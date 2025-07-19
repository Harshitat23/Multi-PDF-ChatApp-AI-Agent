# Multi-PDF-ChatApp-AI-Agent

# 🚀 Overview

Enterprises handle thousands of unstructured documents like contracts, invoices, and reports. Extracting useful information from such files manually is time-consuming and error-prone.

This project presents an AI-powered document question-answering system that leverages:

-> OCR for reading scanned PDFs

-> Vision Transformers for understanding visual context

-> Embeddings + Vector Store (FAISS) for fast retrieval

-> RAG (Retrieval-Augmented Generation) to generate accurate, context-aware answers using LLMs

🔍 Ask natural language questions across multiple PDFs and receive contextual answers based on actual document content.

# 🧠 Key Features

📄Multi-PDF Support — Upload multiple documents at once

👁️ Visual Understanding — Uses Vision Transformer + OCR (Tesseract/Pytesseract) for scanned document comprehension

🔍 Retrieval Pipeline — Extracts embeddings from OCR output, stores in FAISS

🧾 LLM-Powered Answering — Uses a Large Language Model (e.g., OpenAI GPT, LLaMA) for final natural language answers

⚡ RAG Framework — Combines retrieval with generative model output for accurate results

# 🛠️ Tech Stack

OCR	Tesseract (via pytesseract)

Visual Understanding	Vision Transformer (ViT)

Embeddings	Cohere / HuggingFace / OpenAI

Vector Store Pinecone

Language Model T5 via HuggingFace

UI Gradio

# 🧪 Example Use Case

PDFs: Upload 10 invoice documents

Query: "What is the due date on invoice #123?"

Response: "The due date for invoice #123 is March 10, 2024."
