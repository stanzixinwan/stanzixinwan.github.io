---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download PDF]({{ base_path }}/files/Resume_Zixin_Wan.pdf)

Contact
======
- Email: [zixinwan04@gmail.com](mailto:zixinwan04@gmail.com)
- GitHub: [stanzixinwan](https://github.com/stanzixinwan)
- LinkedIn: [zixinwan](https://www.linkedin.com/in/zixinwan/)
- Website: [stanzixinwan.github.io](https://stanzixinwan.github.io)

Education
======
- **Columbia University**, New York, NY  
  M.S. in Computer Science, Aug 2026 – Dec 2027 (expected)

- **Brandeis University**, Waltham, MA  
  B.S. in Computer Science and Biology, Aug 2022 – May 2026  
  GPA: 3.76 / 4.00, *magna cum laude*, Dean's List  
  Coursework: Machine Learning, Natural Language Processing, Linear Algebra, Statistics, Data Structures & Algorithms, Computer Systems, Operating Systems, Theory of Computation

Experience
======
- **Visiting Student Researcher**, Shanghai Jiao Tong University, Shanghai, China  
  June 2026 – Sept 2026  
  - Engineered a high-throughput multimodal data pipeline synchronizing dual-arm joint states and 3-channel RGB camera feeds at 30 FPS, reducing I/O latency by 35% across 100+ manipulation episodes.
  - Scaled SFT and advantage-conditioned policy training for an InternVL-1B vision-language-action model.
  - Improved cross-task policy success rates by 18%, using PyTorch FSDP on an 8×A100 GPU cluster.
  - Built a low-latency human-in-the-loop teleoperation and intervention framework for closed-loop evaluation.

- **Machine Learning Research Assistant**, Van Hooser Lab, Brandeis University, Waltham, MA  
  Sept 2024 – May 2026  
  - Authored and defended an honors thesis on functional decoding and neural tuning dynamics in visual cortex.
  - Architected an automated scientific compute pipeline in Python/MATLAB for 2-photon calcium imaging data, transforming terabytes of raw fluorescence streams into memory-mapped binary representations.
  - Developed 50+ modular feature extraction scripts, cutting data processing time by 40%.
  - Maintained CI/CD workflows for open-source scientific tools (`vhlab-toolbox` and NDI-matlab).

- **Software Engineer Intern**, Noah AI, Remote  
  May 2024 – Aug 2024  
  - Designed and deployed an enterprise hybrid RAG pipeline combining dense vector embeddings (FAISS) with BM25 sparse keyword search over medical literature, improving retrieval and reducing hallucinations by 15%.
  - Implemented Cross-Encoder re-ranking and structured JSON Schema validation layers, enforcing output format constraints across high-concurrency LLM agent workflows.
  - Developed backend microservices using FastAPI and Next.js modules, optimizing API response times.

Projects
======
- **DistIE: Distributed Inference Engine** · Go, C++, Python, gRPC, pybind11  
  Building a multi-node LLM inference stack: a Go gateway for concurrent streaming requests, a C++ core for block-based KV-cache and GPU memory pooling, and Python orchestration for continuous batching. [GitHub](https://github.com/stanzixinwan/distie)

- **Cross-Domain Text-to-SQL System** · PyTorch, Transformers, LoRA/QLoRA, FAISS, Docker, FastAPI  
  Fine-tuned encoder-decoder models with QLoRA on the Spider benchmark, reaching 82% execution accuracy on unseen multi-table schemas. Built a schema-aware RAG pipeline with FAISS and containerized inference behind asynchronous FastAPI endpoints.

- **LLM-Powered Nutrition Tracking Platform** · Python, TypeScript, PostgreSQL, Prisma, Vitest  
  Built an AI agent orchestration system that parses unstructured dietary text into validated macronutrient structures. Designed a high-concurrency PostgreSQL schema with Prisma and CI/CD with Vitest and GitHub Actions (90%+ coverage).

Skills
======
- **Programming:** Python, Java, C/C++/C#, JavaScript, SQL, Go, HTML/CSS
- **Frameworks:** React, Next.js, FastAPI, Node.js, Prisma ORM
- **Dev & infra:** Git, GitHub Actions, Linux, CI/CD, Vitest, PostgreSQL, Docker
- **Libraries:** PyTorch, FAISS, scikit-learn, Pandas, NumPy
