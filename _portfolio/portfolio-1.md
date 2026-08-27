---
title: "DistIE: Distributed Inference Engine"
excerpt: "Go gateway + C++ KV-cache/memory pool + Python continuous batching. A production-style LLM inference stack, not a notebook demo."
collection: portfolio
date: 2026-09-01
link: https://github.com/stanzixinwan/distie
---

[DistIE](https://github.com/stanzixinwan/distie) is a distributed LLM inference engine. The split matches production systems: Go for concurrent serving, C++ for memory and kernels, Python for orchestration.

Highlights
======
- **Go gateway:** gRPC streaming, load balancing, leaky-bucket rate limiting.
- **C++ engine core:** block-based KV-cache and GPU memory pooling (PagedAttention-style), so allocation is not left to Python GC.
- **Python orchestrator:** continuous batching, talking to C++ through pybind11.
- **Serving path:** Protobuf/gRPC between nodes; Docker-oriented deploy.

Code: [github.com/stanzixinwan/distie](https://github.com/stanzixinwan/distie)
