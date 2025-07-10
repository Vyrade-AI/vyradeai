```md
# Vyrade Workflow Generator

Takes a user's problem and returns a structured workflow using LangGraph, classification, RAG, and tool matching.

## 🧠 Tech Stack
- LangChain
- LangGraph
- ChromaDB / FAISS
- OpenAI GPT-4o / Mistral
- Pydantic (schema enforcement)

## 📁 Key Files
- `/chains/` → classification, tool matcher, builder
- `/utils/` → embeddings, scoring, schema
- `main.py` → run end-to-end flow

## 🔍 Input → Output
Input: "I want to automate lead outreach"  
Output: JSON tool stack with 3 subtasks

## 📜 License
MIT
