# Mini RAG Chatbot

A Retrieval-Augmented Generation (RAG) chatbot built using LangChain, Hugging Face Embeddings, FAISS, Google Gemini, and Streamlit.

## Features

* PDF document ingestion
* Document chunking and preprocessing
* Semantic search using embeddings
* FAISS vector database
* Google Gemini integration
* Interactive Streamlit interface

## Tech Stack

* Python
* Streamlit
* LangChain
* Hugging Face Sentence Transformers
* FAISS
* Google Gemini API
* PyPDF

## Project Structure

```text
Mini_RAG_Chatbot/
│
├── app.py
├── data/
├── database/
├── utils/
│   ├── loader.py
│   ├── splitter.py
│   ├── embeddings.py
│   ├── vectorstore.py
│   └── rag_chain.py
│
├── requirements.txt
├── README.md
└── .env
```

## Installation

```bash
git clone <repository-url>
cd Mini_RAG_Chatbot

python -m venv rag_env
rag_env\Scripts\activate

pip install -r requirements.txt
```

## Configure API Key

Create a `.env` file:

```env
GOOGLE_API_KEY=YOUR_API_KEY
```

## Run Application

```bash
python -m streamlit run app.py
```

## Example Questions

* What is a Transformer?
* Explain Self-Attention.
* What is Positional Encoding?

## Future Enhancements

* Multi-PDF support
* Chat history
* ChromaDB integration
* Hybrid Retrieval (BM25 + Vector Search)
* Deployment on Streamlit Cloud

## Author

Tanuj Maddi
