# MultiModel-RAG-Using-CLIP
Multimodel RAG implementation using OPENAI - CLIP

The implementation is for PDF based input.

The tech stack includes
- Fitz (PyMuPDF for reading PDF)
- Transformers
- PIL
- Torch
- Numpy
- Langchain
- OpenAI
- CLIP

The pipeline is 

PDF document -> Extract text and Image -> convert text and image into embeddings using CLIP -> embeddings are stored in FAISS <- Retriever -> Top K documents (text and image embeddings) -> format change for making it compatible for the LLM -> LLM (OPENAI GPT 4.1)

