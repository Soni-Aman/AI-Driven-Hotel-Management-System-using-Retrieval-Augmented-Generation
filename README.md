
AI-Driven Hotel Management System using Retrieval-Augmented Generation (RAG)

StaySmart-RAG is an end-to-end AI-powered hotel management intelligence system that leverages Retrieval-Augmented Generation (RAG) to provide accurate, 
context-aware responses across hotel operations such as bookings, cancellations, SOPs, incidents, guest queries, and feedback analysis.

 Key Features

 Semantic search across hotel documents (PDF, TXT, CSV)
 Context-aware question answering using RAG
 Supports structured & unstructured data
 Handles operational data (bookings, revenue, incidents)
 Domain-specific knowledge base for hotel management
 Fast vector similarity search with ChromaDB

 System Architecture

1. Document Ingestion
   - PDFs (Policies, SOPs)
   - TXT files (Menus, Reviews, Feedback)
   - CSV files (Bookings, Guests, Revenue)

2. Text Processing
   - Recursive chunking with overlap
   - Metadata enrichment

3. Embeddings
   - SentenceTransformers (`all-MiniLM-L6-v2`)
   - Dense vector representations

4. Vector Store
   - ChromaDB (persistent storage)

5. Retrieval
   - Cosine similarity search
   - Top-K relevant context fetching

6. Generation
   - Retrieved context passed to LLM
   - Accurate, grounded responses

 Tech Stack

- Python
- LangChain
- SentenceTransformers
- ChromaDB
- NumPy / Pandas
- Scikit-learn
- UUID
- RAG Architecture

