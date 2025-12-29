---
title: "DreamShaper Interactive Workbench"
excerpt: "Developed a real-time generative prototyping tool mirroring Adobe Firefly, optimizing Stable Diffusion to <1.2s latency using Latent Consistency Models."
collection: portfolio
date: 2025-12-29
header:
  teaser: "dreamshaper-single.png"
---

**Technologies:** Python, PyTorch, Diffusers, Gradio, LCM-LoRA

[<i class="fab fa-github"></i> View on GitHub](https://github.com/rukmininazre/dreamshaper-workbench) &nbsp;&nbsp; [<i class="fas fa-rocket"></i> Live Demo](https://huggingface.co/spaces/rukmininazre/dreamshaper-workbench)

### Description
* **Real-Time Pipeline:** Engineered a sub-second generative prototyping tool that reduces Stable Diffusion inference steps by **90% (50 → 6 steps)** using **Latent Consistency Models (LCM)**, achieving **<1.3s latency** on consumer GPUs while maintaining photorealistic texture fidelity.
* **Parallel Comparison Engine:** Developed a multi-threaded "Design Workbench" capable of transforming a single user sketch into **5 distinct aesthetic variations** (e.g., Cinematic, 3D Render, Anime) simultaneously to accelerate creative iteration cycles.
* **Interactive UI/UX:** Built a full-stack **Gradio** application featuring a custom "Sketch-to-Image" canvas powered by **ControlNet**, with granular controls for guidance scale and seed reproducibility to mirror commercial tools like Adobe Firefly.
