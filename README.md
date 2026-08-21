<div align="center">

# Learn LLMs From Scratch

### Build, Understand, and Reproduce Modern Large Language Models

A comprehensive educational repository for learning the theory, mathematics, implementation, and research behind modern Large Language Models (LLMs).

![Python](https://img.shields.io/badge/Python-3.12+-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Latest-red)
![Status](https://img.shields.io/badge/Status-Active-success)

</div>

---

## Overview

Large Language Models have transformed artificial intelligence, yet understanding **how they actually work** remains challenging.

This repository is a long-term educational project dedicated to building modern LLMs from first principles through mathematical foundations, PyTorch implementations, and research paper studies.

Rather than treating models as black boxes, the goal is to understand every major component—from tokenization and self-attention to complete GPT- and Llama-style architectures—and to reproduce influential research papers along the way.

---

## Repository Goals

- 📚 Learn the mathematics behind modern LLMs
- 🐍 Master Python, Scientific Python, and PyTorch
- ⚙️ Implement transformer components from scratch
- 🤖 Build GPT and Llama-style language models
- 📄 Study influential research papers
- 🧪 Reproduce published experiments
- 🔬 Conduct original research-inspired experiments

---

## Repository Structure

```text
learn-llms-from-scratch/

├── foundations/
├── implementations/
├── architectures/
├── papers/
├── experiments/
├── src/
├── notebooks/
├── docs/
└── templates/
```

---

## Prerequisites

This repository assumes familiarity with:

- Basic Python programming
- Calculus
- Linear Algebra

A detailed learning roadmap is available in **[ROADMAP.md](ROADMAP.md)**.

---

## Installation

### Clone the repository

```bash
git clone https://github.com/<your-username>/learn-llms-from-scratch.git
cd learn-llms-from-scratch
```

### Option 1 — Conda (Recommended)

```bash
conda env create -f environment.yml
conda activate llms-from-scratch
```

### Option 2 — Virtual Environment

```bash
python -m venv .venv
```

#### macOS / Linux

```bash
source .venv/bin/activate
```

#### Windows

```powershell
.venv\Scripts\activate
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

---

## Documentation

| Document | Description |
|----------|-------------|
| 📖 [ROADMAP.md](ROADMAP.md) | Complete learning roadmap |
| 📄 [PAPERS.md](PAPERS.md) | Research paper roadmap |
| 📚 [REFERENCES.md](REFERENCES.md) | Textbooks, papers, and external resources |

---

## Topics

### Foundations

- Mathematics for Machine Learning
- Python
- Scientific Python
- PyTorch

### LLM Components

- Tokenization
- Embeddings
- Self-Attention
- Multi-Head Attention
- Transformers

### Architectures

- GPT
- Llama
- Modern LLM Components

### Research

- Paper Summaries
- Mathematical Derivations
- Paper Implementations
- Experiment Reproductions

---

## Inspiration

This repository has been inspired by the educational work of the AI community, including:

- Sebastian Raschka — *Build a Large Language Model (From Scratch)*
- Andrej Karpathy — *nanoGPT*
- Andrej Karpathy — *llm.c*
- Fareed Khan — *train-llm-from-scratch*
- Hugging Face — *Transformers*

This repository is an original educational project documenting my own understanding through implementations, experiments, and research paper studies.

---

## License

Released under the MIT License.

