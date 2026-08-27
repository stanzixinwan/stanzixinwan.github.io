---
title: "Cross-Domain Text-to-SQL"
excerpt: "Fine-tuned encoder-decoder models with QLoRA and a FAISS RAG stack, reaching 82% execution accuracy on Spider."
collection: portfolio
---

This project is an end-to-end natural-language SQL generation system for complex multi-table schemas.

Highlights
======
- Fine-tuned encoder-decoder models with QLoRA on the Spider benchmark.
- Reached 82% execution accuracy on unseen, complex multi-table relational schemas.
- Built a schema-aware RAG pipeline with FAISS vector indexing.
- Containerized inference with Docker and served it through asynchronous FastAPI endpoints.

The goal was not only higher accuracy, but a reproducible serving path: parameter-efficient fine-tuning, retrieval over schema context, then a packaged API for inference.
