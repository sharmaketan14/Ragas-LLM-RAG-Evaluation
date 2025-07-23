# Ragas‑LLM‑RAG‑Evaluation 🚀

A toolkit to evaluate Retrieval‑Augmented Generation (RAG) systems using the **Ragas** framework. This repository provides pipelines, metrics, and example datasets to benchmark RAG workflows paired with LLMs.

---

## 🔍 Features

- Integrates with the Ragas eval toolkit for robust, component‑wise RAG assessment
- Supports metrics like:
  - **Context Precision**, **Context Recall**, **Faithfulness**, **Answer Relevancy**
- Compares peformcance of different LLMs such as Llama 3.1, Gemma, nemotron & mistral.
- Created a new technique to improve results by comparing Similarity of prompt and answer given.
- Uses POSH Act PDF to form synthetic questions and validate answers to those questions.
