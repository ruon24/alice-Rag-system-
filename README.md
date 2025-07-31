# Alice in Wonderland RAG System

A Retrieval-Augmented Generation (RAG) system built with LangChain that answers questions about Alice in Wonderland using semantic search.

## Features
- Document chunking and embedding
- Vector database storage with Chroma
- Semantic search with HuggingFace embeddings
- Question answering with context

## Setup
1. Clone repository
2. Install dependencies: `pip install -r requirements.txt`
3. Add documents to `data/books/`
4. Create database: `python create_database.py`
5. Query: `python query_data.py "Your question"`

## Files
- `create_database.py` - Index documents into vector database
- `query_data.py` - Query the RAG system
- `get_embedding_function.py` - Embedding utilities
