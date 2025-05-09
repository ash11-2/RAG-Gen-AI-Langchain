# RAG-Gen-AI-Langchain
# 🤖 RAG with Hugging Face – Jupyter Notebook

This project demonstrates how to build a **Retrieval-Augmented Generation (RAG)** pipeline using **Hugging Face models** in a Jupyter Notebook (`RAG_hugging_face.ipynb`). It walks through document ingestion, vector embedding, retrieval, and generation using pre-trained open-source models.

---

## 📓 Notebook Overview

**File**: `RAG_hugging_face.ipynb`

This notebook covers:

- 🔍 Document loading and preprocessing
- 🧬 Embedding generation using `sentence-transformers`
- 🗃️ Vector storage and similarity search with FAISS
- 🤖 Response generation using Hugging Face models (`transformers`)
- 🧪 End-to-end RAG workflow: Query → Retrieve → Generate

---

## 🧰 Tech Stack

| Tool / Library          | Purpose                                      |
|-------------------------|----------------------------------------------|
| `transformers`          | Text generation using language models        |
| `sentence-transformers` | Generating embeddings for retrieval          |
| `faiss`                 | Vector similarity search                     |
| `datasets`              | Sample datasets for demo                     |
| `scikit-learn`          | Optional preprocessing / utilities           |
| `langchain` *(optional)*| High-level RAG abstractions                  |
| `nltk` / `spacy`        | Text cleaning and tokenization (optional)    |

---

## ⚙️ Installation

Install required libraries:

```bash
pip install transformers sentence-transformers faiss-cpu datasets scikit-learn
