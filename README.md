# HealthBuddy-AI-Medical-Chatbot
HealthBuddy AI is a medical chatbot built using Retrieval-Augmented Generation (RAG) that answers healthcare-related questions using knowledge extracted from medical PDF books. The system processes medical documents with LangChain, converts text into vector embeddings using sentence-transformers/all-MiniLM-L6-v2, and stores them in Pinecone for semantic search. Relevant information is retrieved and passed to GPT-4o to generate accurate responses. The chatbot interface is built with Flask and deployed on Hugging Face Spaces.

| Component            | Technology            | Purpose                  |
| -------------------- | --------------------- | ------------------------ |
| Programming Language | Python                | Core development         |
| Orchestration        | LangChain             | Connects LLM, vector DB  |
| LLM                  | GPT-4o                | Response generation      |
| Embedding Model      | Sentence Transformers | Text → vector conversion |
| Vector Database      | Pinecone              | Stores embeddings        |
| Backend              | Flask                 | Web API                  |
| Frontend             | HTML, CSS             | Chat interface           |
| Deployment           | Hugging Face Spaces   | Hosting platform         |

📂 Project Workflow

Load medical PDFs

Extract and clean text

Split text into chunks

Generate embeddings

Store embeddings in Pinecone

Retrieve relevant chunks using similarity search

Send context to GPT-4o

Generate response

Display response in chatbot UI 

⚠️ Disclaimer

This chatbot is designed for educational and informational purposes only.
