---
title: "AI Interview Companion (Second Brain)"
excerpt: "Engineered a full-stack RAG agent on Cloudflare Workers that acts as a personalized mock interviewer. Features an automated Python evaluation pipeline achieving 90% retrieval accuracy."
collection: portfolio
date: 2025-12-25
header:
  teaser: "second-brain-benchmark.png"
---

**Technologies:** Cloudflare Workers, Durable Objects, Vectorize (RAG), Llama 3.3, TypeScript, Python

[<i class="fas fa-link"></i> Live Demo](https://cf-ai-second-brain.rnazre.workers.dev) | [<i class="fab fa-github"></i> View on GitHub](https://github.com/rukmini-17/cf_ai_second_brain)

### Description

* **RAG Architecture:** Built a serverless **Retrieval-Augmented Generation** system using Cloudflare Vectorize. It converts user notes (STAR stories, technical definitions) into 1024-dimensional embeddings, allowing the Llama 3.3 LLM to recall specific personal experiences during mock interviews.
* **Engineering Rigor:** Developed a custom **Offline Evaluation Pipeline** in Python (`sentence-transformers`). This automated benchmark regression-tests the agent's memory, validating a **90.3% semantic accuracy** against a "Golden Dataset" of ground-truth answers.
* **State Management:** Implemented **Durable Objects** to manage real-time WebSocket connections and chat history, ensuring consistent context retention across distributed edge locations.

<br>

![Benchmark Results](/images/second-brain-benchmark.png)

*Figure: Automated benchmarking results showing >90% accuracy in retrieving Personal History and ML concepts.*
