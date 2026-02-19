# touristinfo.ai — Technical Interview Exercise

## Task
Build a minimal RAG pipeline for a tourism chatbot.

You have a small dataset of tourism documents (South Tyrol destinations).
Your goal: given a user query, retrieve relevant documents and generate a response using an LLM.

## Requirements
- Chunk and embed the provided documents into a vector store
- Retrieve the top-k relevant chunks for a given query
- Generate a response using an LLM with the retrieved context

## Constraints
- Use Python
- Use any vector store you're comfortable with (ChromaDB, FAISS, Qdrant, etc.)
- Use any LLM provider (OpenAI, Anthropic, local model, etc.) — we'll provide an API key during the session
- No UI needed, a script or notebook is fine
- You have ~30-40 minutes

## What we're looking for
- Working code that solves the problem
- Pragmatic decisions over perfect ones
- Clean, readable implementation
- How you debug when things don't work

## Getting started
```bash
pip install -r requirements.txt
```

