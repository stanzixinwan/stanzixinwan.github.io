---
title: "DistIE: Distributed Inference Engine"
excerpt: "A production-oriented LLM inference stack: Go for high-concurrency serving, C++ for KV-cache and memory, Python for orchestration."
collection: portfolio
link: https://github.com/stanzixinwan/distie
---

[DistIE](https://github.com/stanzixinwan/distie) is a distributed, high-throughput LLM inference engine I am building as a systems project. The idea is to split the stack the way production engines do: a Go gateway for concurrent requests, a C++ core for memory and kernels, and Python for model orchestration.

Highlights
======
- **Go gateway:** gRPC streaming, load balancing, and leaky-bucket rate limiting for high-concurrency prompts.
- **C++ engine core:** block-based KV-cache and GPU memory pooling (PagedAttention-style), so allocation is not left to Python GC.
- **Python orchestrator:** continuous batching and the inference loop, talking to the C++ core through pybind11.
- **Serving path:** Protobuf/gRPC between nodes, with Docker-oriented deployment.

The project is meant to look like a real inference system (in the spirit of vLLM / TGI), not a notebook demo: request path, memory manager, and a measurable serving loop.

Code: [github.com/stanzixinwan/distie](https://github.com/stanzixinwan/distie)
