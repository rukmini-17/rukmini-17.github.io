---
title: "SentinEdge: Real-Time Fraud Detection & Data Engineering Pipeline"
excerpt: "Engineered a high-throughput streaming pipeline using PySpark, Kafka, and DynamoDB, achieving 99.21% accuracy in real-time anomaly detection."
collection: portfolio
date: 2026-02-18
header:
  teaser: "sentinedge_metrics.png"
  priority: 1
---

**Technologies:** PySpark 3.5, Apache Kafka (KRaft), Amazon DynamoDB, Docker, Parquet, Python 3.9, Boto3

[<i class="fab fa-github"></i> View on GitHub](https://github.com/rukmini-17/SentinEdge)

### Description
* **Real-Time Streaming Architecture:** Engineered a high-throughput pipeline using **PySpark Structured Streaming** and **Apache Kafka** to process financial transactions with sub-second latency.
* **Stateful Feature Store:** Implemented a low-latency feature store using **Amazon DynamoDB** to track rolling historical user behavior, enabling real-time comparisons between incoming events and individual spending averages.
* **Medallion Data Lake:** Architected a multi-layer storage strategy, persisting enriched "Silver" data into **Snappy-compressed Parquet** files for long-term auditing and model retraining.
* **High-Fidelity Detection:** Achieved a detection accuracy of **99.21%** with a **90.00% Recall** rate, optimizing the pipeline to minimize false negatives in a high-risk financial environment.
* **Robust Distributed Processing:** Resolved complex **serialization (pickling)** challenges and implemented **Spark Checkpointing** to ensure exactly-once processing and fault tolerance across distributed worker nodes.
* **Automated MLOps Auditing:** Developed a custom evaluation suite to calculate Precision (**94.03%**) and Recall metrics automatically, providing a continuous feedback loop for heuristic tuning.
