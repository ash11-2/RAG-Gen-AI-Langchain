# Enterprise Search Assistant with RAG + Agentic AI (LangChain)

This project implements an intelligent **Enterprise Search Assistant** that can answer questions using your company's internal documentation. It uses **Retrieval-Augmented Generation (RAG)** and **Agentic AI** concepts via **LangChain** and **OpenAI** to provide context-aware responses, grounded in your internal knowledge base.

---

##  Features

-  Load and index company knowledge base (text files)
-  RAG-powered retrieval using OpenAI embeddings and FAISS
-  Agent framework with tool-use (LangChain Tools)
-  Conversational memory with GPT-4
-  Interactive Q&A loop for internal team use

---

##  Tech Stack

| Component     | Tech Used                |
|---------------|--------------------------|
| LLM           | OpenAI GPT-4             |
| Embeddings    | OpenAI Embeddings        |
| Vector Store  | FAISS                    |
| Agentic Layer | LangChain Tools & Agent  |
| Memory        | LangChain BufferMemory   |
| Loader        | LangChain `TextLoader`   |

---

##  Project Structure

