```md
# Vyrade RAG Engine

RAG pipeline used to retrieve tool data from vector DBs based on user intent.

## 📦 Features
- ChromaDB or FAISS backend
- Dense embeddings from OpenAI or Sentence Transformers
- Fallback logic + summarization chains

## 🔧 Files
- `/retrievers/` → DB wrappers
- `/rag_flows/` → RAG + summarizer chains

## 💬 Used In:
- `workflow-generator`
- Vyrade backend API
