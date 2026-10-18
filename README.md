# Simple-RAG-LangChain-Project

Purpose: Build a question-answering system that retrieves relevant information from documents and generates context-aware responses using LangChain and Google Gemini.

RAG Workflow:

Document Loading: Load source documents.

Text Splitting: Divide documents into manageable chunks.

Embedding Generation: Convert text chunks into vectors using gemini-embedding-001.

Vector Storage: Store and index embeddings in Chroma.

Retrieval: Find relevant document chunks using semantic search.

Prompt Augmentation: Combine retrieved context with the user's question.

Answer Generation: Use gemini-3.8-flash to generate a context-aware response.

Key Components: LangChain, Google Gemini LLM, Gemini Embeddings, Chroma Vector Database, Retriever, and Prompt Template.

Learning Outcomes: Understand RAG architecture, semantic search, vector databases, prompt engineering, API configuration, and troubleshooting model and dependency errors.
