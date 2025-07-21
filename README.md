# 🧠 Evaluating LLMs as Semantic Judges of RDF Triples

This repository contains the code, data, and evaluation pipeline used in our study to assess the ability of Large Language Models (LLMs) to judge the semantic correctness of RDF triples generated from natural language texts.

Our evaluation framework includes comparisons with human annotations, multiple LLM configurations (few-shot and zero-shot), and a meta-evaluation phase to verify consistency of model-generated justifications.

## 📄 Overview

The methodology implemented here evaluates how well LLMs can determine whether a given RDF triple accurately represents a summarized sentence from e-commerce question–answer interactions.

Key components of the evaluation pipeline include:

- A dataset of real-world sentence–triple pairs
- Prompts for LLM-based evaluation
- Multiple LLM configurations (e.g., Qwen, Gemma, Sabiá)
- A gold standard annotated by experts
- Consistency checks by a larger LLM (DeepSeek)
- Statistical analysis of LLM vs. human agreement



---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.9+
- API access to your preferred LLMs (OpenAI, HuggingFace, etc.)
- Jupyter Notebook (for result analysis)

### 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/llm-rdf-evaluation.git
cd llm-rdf-evaluation
```