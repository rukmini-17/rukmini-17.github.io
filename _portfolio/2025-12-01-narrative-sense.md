---
title: "Narrative Sense Disambiguation with LLMs"
excerpt: "Engineered a graded word-sense plausibility pipeline using DeBERTa, RoBERTa, and GPT-4 to quantify semantic ambiguity."
collection: portfolio
date: 2025-12-01
header:
  teaser: "nlp.png"
---

**Technologies:** PyTorch, Hugging Face, GPT-4, LoRA

[<i class="fab fa-github"></i> View on GitHub](https://github.com/a-bhavana04/word-sense-plausibility)

### Description
* **Pipeline Engineering:** Engineered a graded **word-sense plausibility pipeline**, fine-tuning Transformer architectures (**DeBERTa, RoBERTa**) to quantify semantic ambiguity in narrative contexts.
* **Synthetic Data Generation:** Designed and implemented a synthetic data generation system using **GPT-4** with structured prompting; generated ~800 ambiguity-rich samples that **improved encoder rank correlation (Spearman's ρ) by over 10%**.
* **LLM Benchmarking:** Developed an automated **LLM-as-a-Judge** framework to benchmark **Mistral-7B** and **Qwen-2.5** against human annotators, implementing **LoRA fine-tuning** to optimize performance on resource-constrained hardware.
