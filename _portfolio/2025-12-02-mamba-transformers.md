---
title: "Scalable Sequence Modeling: Mamba vs. Transformers"
excerpt: "Benchmarked Mamba (Selective SSM) and Transformer architectures to investigate trade-offs in computational complexity and memory scaling."
collection: portfolio
date: 2025-12-02
header:
  teaser: "mamba.png"
---

**Technologies:** Python, PyTorch, CUDA

[<i class="fab fa-github"></i> View on GitHub](https://github.com/rukmini-17/scalable-sequence-modeling)

### Description
* **Architecture Implementation:** Implemented and benchmarked Mamba (Selective SSM) and Transformer architectures from scratch to investigate trade-offs in **computational complexity** ($\mathcal{O}(L)$ vs $\mathcal{O}(L^2)$) and **memory scaling**.
* **Performance Analysis:** Conducted rigorous performance analysis, demonstrating Mamba's superior efficiency with a **Test Loss of 1.80** (vs. 1.86 for Transformer) while enabling **constant-time inference**.
* **Optimization:** Executed extensive hyperparameter sweeps (state dimension, head count) to optimize next-token prediction, aligning with research into **resource-efficient ML systems**.
