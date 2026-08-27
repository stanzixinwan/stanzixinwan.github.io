---
title: "Vision-Language-Action Policy Training"
excerpt: "Built multimodal robot data pipelines and scaled InternVL-1B VLA training on an 8×A100 cluster at Shanghai Jiao Tong University."
collection: portfolio
---

As a visiting student researcher at Shanghai Jiao Tong University, I worked on data infrastructure and training for vision-language-action models in bimanual manipulation.

Highlights
======
- Engineered a high-throughput pipeline that synchronized dual-arm joint states with 3-channel RGB video at 30 FPS.
- Reduced I/O latency by 35% across 100+ manipulation episodes.
- Scaled SFT and advantage-conditioned policy training for an InternVL-1B VLA model with PyTorch FSDP on 8×A100 GPUs.
- Improved cross-task policy success rates by 18%.
- Built a low-latency human-in-the-loop teleoperation stack for closed-loop evaluation.

This work sits at the intersection of robotics systems and large-model training: collecting clean multimodal demonstrations, then turning them into policies that can be evaluated in the loop.
