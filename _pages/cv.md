---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **M.S. in Computer Science**, University of Massachusetts Amherst, 2027 (Expected)
* **B.Tech. in Computer Engineering**, College of Engineering Pune, 2025
  * *Honors in Data Science, CGPA: 8.59/10*

Work Experience
======
* **Summer 2024: Research Intern**, TCS Research (Pune, India)
  * Curated a structured dataset of character relations from unstructured narrative text (Harry Potter corpus).
  * Conducted comparative experiments with multilabel classification algorithms (Random Forest, SVM, Neural Networks) using LLM embeddings (BERT, DistilBERT), achieving 89.6% accuracy.
  * Designed and implemented a Neo4j-based knowledge graph for analyzing relational structures.
  * *Technologies:* Python, PyTorch, Neo4j

Skills
======
* **Programming Languages:** Python, C++, Java, C, JavaScript, R, Julia
* **Databases & Web:** SQL, MongoDB, Cassandra, Neo4j, HTML/CSS, Node.js, Express, React
* **ML Frameworks & Tools:** PyTorch, LangChain, Hugging Face, Scikit-learn, TensorFlow, Spark, Kafka, Docker, Linux, LaTeX

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Projects
======
* **AI Interview Companion (RAG Agent)** (Dec 2025): Engineered a serverless RAG system using Cloudflare Workers and Vectorize, featuring a custom Python evaluation pipeline that validated 90.3% semantic retrieval accuracy against ground-truth interview data.
* **Narrative Sense Disambiguation with LLMs** (Dec 2025): Engineered a word-sense plausibility pipeline using DeBERTa/RoBERTa and GPT-4 synthetic data.
* **Scalable Sequence Modeling (Mamba vs. Transformers)** (Dec 2025): Benchmarked computational complexity and memory scaling of Selective SSMs.
* **Reverse-Mode Automatic Differentiation Engine** (Oct 2025): Developed a computational graph framework from scratch to enable gradient computation via backpropagation; engineered 11 core operations including matmul and logdet.
* **TERRA-CD: Semantic Change Detection** (March 2025): Created a benchmark dataset of 5,221 paired Sentinel-2 images; trained Siamese networks for change detection.
