# RAG playground

## Advanced_RAG_with_LangChain.ipynb

This notbook demonstrates building a Retrieval-Augmented Generation (RAG) model using LangChain for question answering. 

It features:
- Embeddings Retriever: Chunks knowledge base documents, leverages FAISS for efficient nearest neighbor search.
- LLM Reader: Interprets retrieved contexts and generates answers, using a structured prompt template for optimal results.
- Reranking: Employs RAGatouille library to initially retrieve and rerank a large set of documents, ensuring only the most relevant are used for answer generation.
