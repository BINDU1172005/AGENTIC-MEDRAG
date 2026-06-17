# AGENTIC-MEDRAG
# 🧬 Agentic Hybrid RAG

## Overview

Agentic Hybrid RAG is a Multi-Agent Research Intelligence System designed to analyze engineering and healthcare research papers using Retrieval-Augmented Generation (RAG).

The system combines semantic search, keyword search, knowledge graph generation, research gap identification, and LLM-powered reasoning to help researchers quickly extract insights from large collections of research documents.

---

## Key Features

### 📄 Document Ingestion

* Upload multiple PDF research papers
* Automatic text extraction and preprocessing
* Intelligent chunking and indexing

### 🔍 Hybrid Retrieval

* FAISS Vector Search
* BM25 Keyword Search
* Reciprocal Rank Fusion (RRF)

### 🤖 Multi-Agent Architecture

* Parsing Agent
* Chunking Agent
* Retrieval Agent
* Extraction Agent
* Validation Agent
* Knowledge Graph Agent

### 🧠 LLM-Powered Reasoning

* LLaMA 3 via Groq API
* Question Answering
* Comparative Analysis
* Research Gap Identification

### 🕸️ Knowledge Graph Generation

* Extracts entities and relationships
* Visualizes connections among:

  * Papers
  * Datasets
  * Methods
  * Metrics
  * Results

### 📊 Analytics Dashboard

* Research trends
* Method comparisons
* Cluster visualizations
* Citation analysis

---

## System Architecture

User Query
↓
Query Classifier
↓
Hybrid Retrieval (FAISS + BM25)
↓
Reciprocal Rank Fusion
↓
Context Selection
↓
LLaMA 3 Generation
↓
Validation Agent
↓
Knowledge Graph + Analytics

---

## Tech Stack

| Category         | Technology            |
| ---------------- | --------------------- |
| Language         | Python                |
| Frontend         | Streamlit             |
| Vector Search    | FAISS                 |
| Keyword Search   | BM25                  |
| LLM              | LLaMA 3 (Groq)        |
| Knowledge Graph  | NetworkX              |
| Visualization    | Plotly                |
| Machine Learning | Scikit-Learn          |
| NLP              | Sentence Transformers |

---

## Installation

```bash
git clone https://github.com/yourusername/Agentic-Hybrid-RAG.git

cd Agentic-Hybrid-RAG

pip install -r requirements.txt

streamlit run app.py
```

---

## Future Enhancements

* Multi-modal document analysis
* Voice-based querying
* Research recommendation engine
* Cloud deployment
* Collaborative research workspace

---

## Author

Bindu D

Computer Science Engineering Student

Research Interests:
Artificial Intelligence, Machine Learning, Information Retrieval, Generative AI
