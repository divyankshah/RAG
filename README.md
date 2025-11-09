# 🔍 Dense Passage Retrieval (DPR) - Similarity Search

This repository demonstrates how to use **Facebook’s Dense Passage Retrieval (DPR)** models from Hugging Face’s `transformers` library to compute **semantic similarity** between a user query and a set of passages.  
DPR is commonly used as the retrieval component in **Retrieval-Augmented Generation (RAG)** systems.

---

## 🧠 Overview

In this example:
- A **question encoder** converts a natural language query into a dense vector.  
- A **context encoder** converts passages into dense vectors.  
- **Cosine similarity** measures how semantically close the query is to each passage.  
- The passage with the highest score is considered the most relevant.

---

## ⚙️ Requirements

Install dependencies:

```bash
pip install torch transformers
