# Alice in Wonderland RAG System

A Retrieval-Augmented Generation (RAG) system built with LangChain that answers questions about Alice in Wonderland using semantic search.

## Features
- Document chunking and embedding
- Vector database storage with Chroma
- Semantic search with HuggingFace embeddings
- Question answering with context
- **Flexible document processing** - works with any text documents

## Setup
1. Clone repository
2. Install dependencies: `pip install -r requirements.txt`
3. **Add your documents to `data/books/`** (supports .md, .txt, .pdf files)
4. Create database: `python create_database.py`
5. Query: `python query_data.py "Your question"`

## Customize Your Data
You can replace the Alice in Wonderland text with **any documents you want to process**:
- Research papers
- Company documentation  
- Books or articles
- Technical manuals
- Personal notes

Simply place your files in the `data/books/` directory and the system will process them automatically!

## Files
- `create_database.py` - Index documents into vector database
- `query_data.py` - Query the RAG system
- `compare_embeddings.py` - Compare word embeddings
