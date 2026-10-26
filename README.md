# Smart PDF Reader with RAG

##  Project Overview
Smart PDF Reader with RAG (Retrieval-Augmented Generation) is an AI-powered application that answers questions based on document content. It retrieves relevant text chunks from a document using a Chroma vector database and generates context-based answers using a local Qwen LLM.

##  Features
- Ask questions about document content.
- Retrieve relevant text chunks using vector search.
- Generate answers using a local Qwen model.
- Display retrieved sources and metadata.
- Evaluate retrieval coverage and answer quality using basic evaluation metrics.

##  Tech Stack
- **Language:** Python
- **LLM:** Qwen2.5-1.5B-Instruct
- **Vector Database:** ChromaDB
- **Frameworks:** Hugging Face Transformers
- **Deep Learning:** PyTorch
- **Evaluation:** Precision, Recall, F1-score, and keyword coverage

##  How It Works
1. Load the document and split it into chunks.
2. Convert chunks into embeddings and store them in ChromaDB.
3. Retrieve relevant chunks for a user question.
4. Pass the retrieved context to the Qwen model.
5. Generate an answer and return source metadata.
6. Evaluate retrieval and answer quality.


##  Learning Outcomes
- Understanding Retrieval-Augmented Generation (RAG).
- Working with embeddings and vector databases.
- Running a local LLM using Hugging Face Transformers.
- Evaluating retrieval and generated answers.

## 🔮 Future Improvements
- Improve chunking and retrieval quality.
- Add semantic evaluation and faithfulness checks.
- Support multiple PDF uploads and document formats.
