# Simple-RAG-LangChain-Project

# 🤖 Simple RAG: Document-Based Question Answering

### 🎯 Purpose
Build an AI-powered question-answering system that retrieves relevant information from documents and generates context-aware responses using **LangChain** and **Google Gemini**.

### 🔄 RAG Workflow

1. 📄 **Document Loading:** Load source documents for processing.
2. ✂️ **Text Splitting:** Divide documents into smaller, manageable chunks.
3. 🔢 **Embedding Generation:** Convert text chunks into numerical vectors using `gemini-embedding-001`.
4. 🗄️ **Vector Storage:** Store and index embeddings in the **Chroma Vector Database**.
5. 🔍 **Retrieval:** Find relevant document chunks using semantic search.
6. 📝 **Prompt Augmentation:** Combine retrieved context with the user's question.
7. 💡 **Answer Generation:** Use `gemini-3.8-flash` to generate context-aware responses grounded in retrieved information.

### 🛠️ Key Components

- 🦜 **LangChain** — RAG workflow orchestration.
- 🧠 **Google Gemini LLM** — Context-aware answer generation.
- 🔢 **Gemini Embeddings** — Semantic representation of text.
- 🗄️ **Chroma Vector Database** — Vector storage and similarity search.
- 🔎 **Retriever** — Fetches relevant document chunks.
- 📝 **Prompt Template** — Structures context and user questions.
- 🔐 **Google API Key** — Authenticates access to Google AI models.

### 📚 Learning Outcomes

- 🔄 Understanding the RAG architecture and workflow.
- 🔍 Implementing semantic search and document retrieval.
- 🗄️ Working with vector databases and embeddings.
- 📝 Applying prompt engineering techniques.
- 🔑 Configuring API authentication securely.
- 🛠️ Troubleshooting API key validation, model availability, dependency conflicts, and chain input mismatches.

### 🚀 Technologies Used

`Python` · `LangChain` · `Google Gemini` · `Chroma` · `Google Colab` · `Jupyter Notebook`
