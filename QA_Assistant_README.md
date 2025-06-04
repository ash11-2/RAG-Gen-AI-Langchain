# Q\&A Assistant using RAG + LangChain Agentic AI

This project implements an intelligent **Question Answering Assistant** that combines **Retrieval-Augmented Generation (RAG)** and **LangChain Agentic AI** concepts using OpenAI and FAISS. The assistant can answer user queries by grounding responses in a provided knowledge base.

---

## Features

* ✅ Context-aware Q\&A based on your documents
* ✅ Agentic decision-making via LangChain Tools
* ✅ Conversational memory support
* ✅ Uses OpenAI GPT-4 for intelligent responses
* ✅ Efficient vector indexing with FAISS

---

## Folder Structure

```
qa-assistant-rag/
├── data/
│   └── knowledge_base.txt     # Your document source
├── assistant.py               # Main application
├── .env                       # Your OpenAI API key
└── README.md                  # This file
```

---

## Setup Instructions

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/qa-assistant-rag.git
cd qa-assistant-rag
```

2. **Install Dependencies**

```bash
pip install langchain openai faiss-cpu python-dotenv
```

3. **Set up API Key**

Create a `.env` file and add your OpenAI key:

```
OPENAI_API_KEY=your-openai-key
```

4. **Prepare the Knowledge Base**

Put your knowledge content into `data/knowledge_base.txt`.

---

## Run the Assistant

```bash
python assistant.py
```

Ask questions like:

```
You: What is the company's leave policy?
Assistant: According to the knowledge base...
```

Type `exit` to quit the program.

---

## How It Works

1. Loads documents and splits them into chunks.
2. Embeds and stores them in a FAISS vector index.
3. Retrieves top relevant chunks per query.
4. Routes queries to a LangChain agent with a tool.
5. Uses GPT-4 to respond contextually.

---

## Next Steps

* [ ] Add support for PDF or HTML documents
* [ ] Create a web UI using Streamlit
* [ ] Use Pinecone or ChromaDB for scalable vector storage
* [ ] Add logging and analytics for queries

---

## License

MIT License

---

## Acknowledgements

* [LangChain](https://github.com/langchain-ai/langchain)
* [OpenAI](https://platform.openai.com/)
* [FAISS](https://github.com/facebookresearch/faiss)
