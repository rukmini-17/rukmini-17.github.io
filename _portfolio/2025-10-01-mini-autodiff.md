---
title: "Mini-AutoDiff: Reverse-Mode Automatic Differentiation"
excerpt: "Built a lightweight Deep Learning framework from scratch using NumPy, featuring a dynamic computational graph engine and reverse-mode differentiation."
collection: portfolio
date: 2025-10-01
header:
  teaser: "autodiff_graph.png"
---

**Technologies:** Python, NumPy, Linear Algebra, Graph Algorithms

[<i class="fab fa-github"></i> View on GitHub](https://github.com/rukmini-17/mini-autodiff)

### Description
* **Core Engine:** Developed a **computational graph framework** from scratch to enable gradient computation via **backpropagation** (reverse-mode differentiation), mimicking the core functionality of PyTorch's `autograd`.
* **Operator Implementation:** Engineered **11 core operations** (including `matmul`, `solve`, `logdet`, and `cholesky`) with custom Vector-Jacobian Products (VJPs) to handle gradient flow through complex linear algebra equations.
* **Advanced Validation:** Successfully validated the engine by computing gradients for a **Multivariate Gaussian Log-Likelihood model** ($\mathcal{L}(\Sigma)$), handling complex derivatives involving matrix inverses and determinants ($\frac{\partial \log|\Sigma|}{\partial \Sigma} = (\Sigma^{-1})^\top$).

<br>

<p align="center">
  <img src="/images/autodiff_graph.png" alt="Computational Graph" width="80%">
</p>
<p align="center"><em>Figure: Visualizing the forward pass (black) and backward gradient flow (red) in the custom engine.</em></p>
