---
title: "Cross-Domain Text-to-SQL"
excerpt: "82% Spider execution accuracy with QLoRA fine-tuning and a FAISS schema-aware RAG serving path."
collection: portfolio
date: 2026-03-01
---

End-to-end natural-language SQL generation for complex multi-table schemas.

Highlights
======
- QLoRA fine-tuning of encoder-decoder models on Spider.
- 82% execution accuracy on unseen multi-table schemas.
- Schema-aware RAG with FAISS.
- Dockerized inference behind asynchronous FastAPI.

Built as a full serving path (train → retrieve schema context → API), not only a training run.
