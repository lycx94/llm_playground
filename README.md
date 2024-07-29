# RAG playground

## RAG_ollama_pdf.ipynb
This notebook showcases a RAG implementation using Ollama for processing PDF documents. It demonstrates how to extract information from PDFs and use it for question answering. Key features include:


**Two chunking methods:**

- Recursive chunking
- Semantic chunking

**Retrieval mechanisms:**
- FAISS (Facebook AI Similarity Search) as the primary retriever
- BM25 as an ensemble retriever


## RAG_with_Reranker_for_Question_Answering.ipynb

This notbook demonstrates building a Retrieval-Augmented Generation (RAG) model using LangChain for question answering. 

It features:
- Embeddings Retriever: Chunks knowledge base documents, leverages FAISS for efficient nearest neighbor search.
- LLM Reader: Interprets retrieved contexts and generates answers, using a structured prompt template for optimal results.
- Reranking: Employs RAGatouille library to initially retrieve and rerank a large set of documents, ensuring only the most relevant are used for answer generation.

## RAG_using_Llama3_with_Reranking_for_Github_Issues.ipynb
This notbook demonstrates building a Retrieval-Augmented Generation (RAG) model using LangChain for GitHub issues. The RAG system is enhanced with the ColBERT reranker to improve the relevance of retrieved documents. 

- GitHub Repository: Run-llama/llama_index
- Embedding Model: BAAI/bge-base-en-v1.5
- LLM: Llama-3-8b-chat-hf
- Reranker: ColBERTv2.0


