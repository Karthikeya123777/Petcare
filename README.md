# 🐾 Pet Care AI Chatbot

An AI-powered Pet Care Medical Chatbot built using Python, Streamlit, and LangChain.

## Features
- Upload veterinary PDF documents
- Ask natural language questions about pet health
- Get accurate, domain-grounded answers using RAG (Retrieval-Augmented Generation)

## Tech Stack
- **UI**: Streamlit
- **PDF Parsing**: PyPDF2
- **Embeddings**: HuggingFace `gte-large`
- **Vector Store**: FAISS
- **LLM**: CTransformers (local, CPU)
- **Chain**: LangChain RetrievalQA

## How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Author
Karthikeya123777.
