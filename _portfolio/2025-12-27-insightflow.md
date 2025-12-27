---
title: "InsightFlow: Serverless AI Analytics Agent"
excerpt: "Engineered a serverless AI agent on Cloudflare Workers that converts natural language to SQL and performs real-time sales forecasting."
collection: portfolio
date: 2025-12-27
header:
  teaser: "insightflow1.png"
---

**Technologies:** Cloudflare Workers, D1 (SQLite), Llama 3, TypeScript

[<i class="fab fa-github"></i> View on GitHub](https://github.com/rukmini-17/insightflow-agent)

### Description
* **Serverless Architecture:** Architected a full-stack AI agent entirely on **Cloudflare Workers**, utilizing **D1 (SQLite)** for edge storage to process sales data with <50ms cold starts.
* **Text-to-SQL Engine:** Integrated **Llama 3-8b** via Workers AI to translate natural language questions (e.g., *"Top 3 products by revenue"*) into valid SQL queries with **92% accuracy**.
* **Predictive Analytics:** Engineered a custom **Linear Regression algorithm** from scratch in TypeScript (Least Squares method) to generate real-time revenue forecasts, eliminating dependencies on external Python ML libraries.
