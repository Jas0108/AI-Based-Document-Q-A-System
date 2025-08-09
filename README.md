The AI-Powered Document Q&A System combines a modern Large Language Model (LLM) with a Retrieval-Augmented Generation (RAG) pipeline to deliver fast, accurate, and context-rich answers from your uploaded documents.

How it works:

1) Document Ingestion — Upload your file (PDF, TXT, etc.), and the system extracts its text.

2) Chunking & Embedding — The text is split into smaller chunks and converted into vector embeddings.

3) Vector Search — A FAISS-powered semantic search retrieves only the most relevant chunks.

4) Answer Generation — The LLM processes your question and the retrieved context to produce a precise answer.

Tech Stack:
Language: Python 3.10+
Framework: LangChain
LLM: Llama3-8b-8192
Embeddings: GoogleGenerativeAIEmbeddings
Vector Store: FAISS
Frontend:Streamlit
Document Parsing: PyPDF2

