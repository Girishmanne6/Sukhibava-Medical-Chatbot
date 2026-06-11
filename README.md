---
title: Sukhibava
emoji: 🏥
colorFrom: blue
colorTo: green
sdk: docker
pinned: false
---

# Sukhibava - Medical Chatbot

A RAG-based medical Q&A chatbot built with LangChain, FAISS, Sentence Transformers, and GPT-4o-mini. Features semantic search over a medical knowledge base with conversation memory.

## Screenshots

| Welcome screen | Medical Q&A | Source citations |
|----------------|-------------|-------------------|
| ![Sukhibava welcome](docs/screenshot-welcome.png) | ![Sukhibava chat](docs/screenshot-chat.png) | ![Sukhibava sources](docs/screenshot-sources.png) |

## Stack

- **LangChain** — RAG pipeline and conversation memory
- **FAISS** — vector search over medical documents
- **Sentence Transformers** — embeddings
- **GPT-4o-mini** — answer generation
- **Chainlit** — chat UI