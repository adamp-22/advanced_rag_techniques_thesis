# Agentic RAG for Document-Based Question Answering

> 🗓️ **Project originally created on: February 26, 2025**

This repository supports my Bachelor's thesis exploring advanced Retrieval-Augmented Generation (RAG) techniques, culminating in the implementation of an agentic RAG system. The goal is to investigate whether incorporating agentic workflows leads to better factual accuracy and reasoning performance in document-based QA.

---

## 🧠 Motivation

Large Language Models (LLMs) are known to hallucinate or provide factually incorrect information when faced with questions beyond their training data. RAG offers a practical solution by retrieving relevant context from external sources, grounding the generated answers in reality. This project explores a variety of RAG strategies, including:

- Semantic chunking
- Parent-child retrieval
- Reranking (Cross-Encoder, LLM-based)
- Hypothetical Document Embeddings (HyDE)
- RAPTOR
- GraphRAG
- Agentic planning and decision-making

---

## 📄 Dataset

All techniques are evaluated using NVIDIA’s **2024 10-K annual report** — a realistic, complex, and domain-specific document that provides a meaningful testbed for document question answering.

---

## ⚙️ Core Technologies

- **LangChain**: For building and chaining retrieval and generation pipelines
- **FAISS**: High-performance dense vector similarity search
- **OpenAI**: Embeddings (`text-embedding-3-large`) and generation (`gpt-4o-mini`)
- **LangSmith**: Pipeline evaluation and observability

---

## 📊 Evaluation

Each RAG system is evaluated on a fixed set of 20 hand-crafted questions, covering both simple fact-based and multi-step reasoning queries. Metrics include:

- Answer correctness
- Retrieval relevance
- Factual grounding
- Latency
- Cost efficiency

---


## 👤 Author and Creation Date 

**Adam Parkanyi**  
