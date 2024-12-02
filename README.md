# RAG (Retrieval-Augmented Generation) Python Solution with Llama3, LangChain, Ollama, and ChromaDB

## Description
This project implements a Retrieval-Augmented Generation (RAG) solution using Flask API for querying documents. The solution integrates state-of-the-art AI models and technologies such as Llama3, LangChain, Ollama, and ChromaDB for efficient document retrieval and generation of contextual responses. 

The system allows users to upload PDF documents, which are processed and stored in a vector database (ChromaDB). When users query the document, the system retrieves relevant information and generates answers based on the context using Llama3 through LangChain, providing accurate and insightful responses.

### Key Features:
- **PDF Upload and Processing**: Users can upload PDF files, which are processed and split into manageable chunks for indexing in the vector database.
- **Document Retrieval**: Using ChromaDB, the solution retrieves the most relevant documents based on the user’s query.
- **AI-driven Response Generation**: The system utilizes Llama3 and Ollama models through LangChain to generate contextually relevant answers based on the retrieved documents.
- **Flask API**: Exposes endpoints to interact with the system, making it easy to integrate and deploy.

### Technologies Used:
- **Llama3**: A language model for generating human-like responses.
- **LangChain**: A framework for building applications that leverage language models.
- **Ollama**: Used for executing Llama3 model queries.
- **ChromaDB**: A vector database for efficient document storage and retrieval.
- **Flask**: A lightweight web framework for building the API.

