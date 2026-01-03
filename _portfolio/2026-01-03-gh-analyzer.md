---
title: "gh-analyzer: High-Performance GitHub Repository Analyzer"
excerpt: "Developed a concurrent CLI tool in Go that analyzes GitHub repository statistics in under 200ms using Goroutines."
collection: portfolio
date: 2026-01-03
header:
  teaser: "gh-analyzer.png"
---

**Technologies:** Go (Golang), Cobra, GitHub API, Concurrency

[<i class="fab fa-github"></i> View on GitHub](https://github.com/rukmini-17/gh-analyzer)

### Description
* **High-Performance CLI:** Engineered a command-line tool using **Go** and **Cobra** to fetch and analyze GitHub repository metrics (Stars, Forks) for large organizations.
* **Concurrency Optimization:** Implemented **Goroutines** and **Channels** to process API requests in parallel, achieving a **~90% reduction in latency** (e.g., analyzing 20+ repositories in **<200ms** vs. sequential execution).
* **Production Engineering:** Designed a robust architecture with **unit testing**, rate-limit handling, and **CI/CD integration** via GitHub Actions to ensure reliability.
