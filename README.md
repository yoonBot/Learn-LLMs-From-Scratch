<div align="center">

# Learn LLMs From Scratch

### Build Modern Large Language Models from First Principles

A comprehensive educational repository dedicated to understanding, implementing, and reproducing modern Large Language Models (LLMs) from scratch.

![Python](https://img.shields.io/badge/Python-3.12+-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Latest-red)
![Status](https://img.shields.io/badge/Status-Active-success)

</div>

---

# Overview

Large Language Models have rapidly transformed artificial intelligence, yet many learning resources either focus heavily on theory or provide implementations with little explanation.

This repository aims to bridge that gap by combining mathematical foundations, PyTorch implementations, and research paper studies into a single structured learning resource.

The long-term goal is to understand **why** modern LLMs work—not just how to use them.

---

# Repository Goals

This repository aims to:

- 📚 Build a strong mathematical foundation for LLMs
- 🐍 Learn Python, Scientific Python, and PyTorch
- ⚙️ Implement transformer components from scratch
- 🤖 Build GPT and Llama-style models
- 📄 Study and summarize influential research papers
- 🧪 Reproduce published experiments
- 🔬 Develop original experiments inspired by modern LLM research

---

# Repository Structure

```text
learn-llms-from-scratch/

├── foundations/
├── concepts/
├── models/
├── papers/
├── experiments/
├── src/
├── notebooks/
├── docs/
└── templates/
```

---

# Prerequisites

This repository assumes basic familiarity with:

- Python programming
- Linear Algebra
- Calculus

A complete prerequisite roadmap is available in **[ROADMAP.md](ROADMAP.md)**.

---

# Getting Started

## Clone the repository

```bash
git clone https://github.com/yourusername/learn-llms-from-scratch.git
cd learn-llms-from-scratch
```

## Create a virtual environment

### Using `venv`

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

### Or using Conda

```bash
conda env create -f environment.yml
conda activate llms-from-scratch
```

## Install dependencies

```bash
pip install -r requirements.txt
```

---

# Documentation

| Document | Description |
|----------|-------------|
| 📖 [ROADMAP.md](ROADMAP.md) | Complete learning roadmap |
| 📄 [PAPERS.md](PAPERS.md) | Research paper roadmap |
| 📚 [REFERENCES.md](REFERENCES.md) | Textbooks, papers, and external resources |

---

# Topics Covered

## Foundations

- Mathematics for Machine Learning
- Python
- Scientific Python
- PyTorch

## Core Concepts

- Tokenization
- Embeddings
- Self-Attention
- Multi-Head Attention
- Transformers

## Large Language Models

- GPT
- Llama
- Modern LLM Architectures
- Training
- Fine-Tuning
- Inference

## Research

- Research paper summaries
- Mathematical derivations
- Paper implementations
- Experiment reproductions

---

# Inspiration

This repository is inspired by the educational work of the AI community, including:

- Sebastian Raschka — *Build a Large Language Model (From Scratch)*
- Andrej Karpathy — *nanoGPT*
- Andrej Karpathy — *llm.c*
- Fareed Khan — *train-llm-from-scratch*
- Hugging Face — *Transformers*

The purpose of this repository is not to replicate these projects, but to develop my own understanding while documenting the learning process through implementations, experiments, and research paper studies.

---

# License

This project is released under the MIT License.
