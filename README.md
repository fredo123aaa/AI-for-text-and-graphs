# 🧠 AI for Text and Graphs

This repository contains practical labs and experiments exploring **Artificial Intelligence methods for text and graph data**, as part of coursework and personal research. The project is currently **in development** and will evolve over the coming weeks.

---

## 📘 Overview

The repo contains Jupyter notebooks that apply and analyze a variety of **machine learning and deep learning techniques** to structured (graphs) and unstructured (text) data.

The objectives are:
- To explore **representation learning** for textual and graph data.
- To understand and implement **graph neural networks (GNNs)** and **natural language processing (NLP)** models.
- To compare classical and neural approaches for learning and prediction.
- To document the learning process and results progressively.

---

## 🧩 Contents

| Notebook | Description |
|-----------|--------------|
| `Lab1_Alejos-Arrieta_Fredo.ipynb` | Implementation of a sequence-to-sequence (seq2seq) architecture with a global attention mechanism for English-to-French translation using PyTorch. |
| `Lab2_Alejos_Arrieta_Fredo.ipynb` | Implementation of memory-efficient instruction tuning for the Qwen2.5-0.5B model using 4-bit quantization and LoRA (Low-Rank Adaptation) to transform a base LLM into a specialized assistant. |
| `Lab3_Alejos_Arrieta_Fredo.ipynb` | Reinforcement Learning from Human Feedback (RLHF) — fine-tuning the Qwen2.5-0.5B-Instruct model on French data using Direct Preference Optimization (DPO) and Generalized Reward Preference Optimization (GRPO) to explore alignment techniques for large language models. |
|`Lab4_Alejos_Arrieta_Fredo.ipynb`| Model Distillation & Retrieval-Augmented Generation (RAG). Part 1 covers synthetic data creation, log-probability extraction from a 7B model, KL-divergence-based distillation into a smaller model, and training utilities. Part 2 builds and evaluates a RAG pipeline on Wikipedia data, including retriever construction and context-aware LLM generation. |

---

## 🚀 Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/fredo123aaa/AI-for-text-and-graphs.git
   cd AI-for-text-and-graphs
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open and run the labs sequentially to follow the progression of methods and insights.

---

## 👤 Author

**Fredo Alejos Arrieta**  
📍 École Polytechnique — Data Science & AI specialization
