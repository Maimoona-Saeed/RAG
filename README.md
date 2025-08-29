# RAG: Minimal Modern Retrieval-Augmented Generation Pipeline

RAG is a minimal end-to-end **Retrieval-Augmented Generation (RAG)** pipeline in Python. It enables context-aware question answering using semantic search and GPT-3.5.

---

## Features

- Text preprocessing and sentence-level chunking
- Semantic embeddings with `sentence-transformers`
- Fast similarity search with FAISS
- Prompt construction for GPT-3.5
- Single and batch query support
- Retrieval visualization (similarity scores)

---

## Installation

```bash
pip install sentence-transformers faiss-cpu openai nltk matplotlib


