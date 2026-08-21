# Research Paper Roadmap

This document outlines the research papers that will be studied, implemented, and reproduced throughout this repository.

The roadmap follows the historical progression of neural language models and modern Large Language Models.

---

## Legend

| Symbol | Meaning |
|---------|---------|
| 📖 | Read |
| ✍️ | Notes & Mathematical Derivations |
| 💻 | Implementation |
| 🧪 | Experiment Reproduction |
| ⭐ | Completed |

---

# Stage 1 — Word Representations

These papers introduced dense vector representations of language.

| Paper | Read | Notes | Implementation | Reproduction |
|------|:---:|:---:|:---:|:---:|
| Efficient Estimation of Word Representations in Vector Space (Word2Vec, 2013) | ⬜ | ⬜ | ⬜ | ⬜ |
| Distributed Representations of Words and Phrases and their Compositionality (Negative Sampling, 2013) | ⬜ | ⬜ | ⬜ | ⬜ |
| GloVe: Global Vectors for Word Representation (2014) | ⬜ | ⬜ | ⬜ | ⬜ |

---

# Stage 2 — Sequence Models

Neural machine translation before Transformers.

| Paper | Read | Notes | Implementation | Reproduction |
|------|:---:|:---:|:---:|:---:|
| Sequence to Sequence Learning with Neural Networks (2014) | ⬜ | ⬜ | ⬜ | ⬜ |
| Neural Machine Translation by Jointly Learning to Align and Translate (Bahdanau Attention, 2014) | ⬜ | ⬜ | ⬜ | ⬜ |
| Pointer Networks (2015) | ⬜ | ⬜ | ⬜ | ⬜ |

---

# Stage 3 — Transformer Revolution

The papers that changed NLP forever.

| Paper | Read | Notes | Implementation | Reproduction |
|------|:---:|:---:|:---:|:---:|
| Attention Is All You Need (2017) | ⬜ | ⬜ | ⬜ | ⬜ |
| BERT (2018) | ⬜ | ⬜ | ⬜ | ⬜ |
| GPT (2018) | ⬜ | ⬜ | ⬜ | ⬜ |
| GPT-2 (2019) | ⬜ | ⬜ | ⬜ | ⬜ |
| GPT-3 (2020) | ⬜ | ⬜ | ⬜ | ⬜ |

---

# Stage 4 — Scaling Laws

Understanding why larger models perform better.

| Paper | Read | Notes | Implementation | Reproduction |
|------|:---:|:---:|:---:|:---:|
| Scaling Laws for Neural Language Models | ⬜ | ⬜ | ⬜ | ⬜ |
| Chinchilla: Training Compute-Optimal Large Language Models | ⬜ | ⬜ | ⬜ | ⬜ |

---

# Stage 5 — Modern LLMs

Modern decoder-only language models.

| Paper | Read | Notes | Implementation | Reproduction |
|------|:---:|:---:|:---:|:---:|
| LLaMA | ⬜ | ⬜ | ⬜ | ⬜ |
| Llama 2 | ⬜ | ⬜ | ⬜ | ⬜ |
| Llama 3 | ⬜ | ⬜ | ⬜ | ⬜ |
| Mistral 7B | ⬜ | ⬜ | ⬜ | ⬜ |
| Mixtral 8x7B | ⬜ | ⬜ | ⬜ | ⬜ |
| DeepSeek-V2 | ⬜ | ⬜ | ⬜ | ⬜ |
| DeepSeek-V3 | ⬜ | ⬜ | ⬜ | ⬜ |
| DeepSeek-R1 | ⬜ | ⬜ | ⬜ | ⬜ |

---

# Stage 6 — Efficient Transformers

Improving Transformer efficiency.

| Paper | Read | Notes | Implementation | Reproduction |
|------|:---:|:---:|:---:|:---:|
| FlashAttention | ⬜ | ⬜ | ⬜ | ⬜ |
| Multi-Query Attention | ⬜ | ⬜ | ⬜ | ⬜ |
| Grouped-Query Attention | ⬜ | ⬜ | ⬜ | ⬜ |
| RoFormer (RoPE) | ⬜ | ⬜ | ⬜ | ⬜ |

---

# Stage 7 — Reasoning

Reasoning and post-training.

| Paper | Read | Notes | Implementation | Reproduction |
|------|:---:|:---:|:---:|:---:|
| Chain of Thought Prompting | ⬜ | ⬜ | ⬜ | ⬜ |
| Self-Consistency | ⬜ | ⬜ | ⬜ | ⬜ |
| Tree of Thoughts | ⬜ | ⬜ | ⬜ | ⬜ |
| DeepSeek-R1 | ⬜ | ⬜ | ⬜ | ⬜ |

---

# Repository Structure

Each paper will have its own directory.

```text
papers/

├── 2013_word2vec/
│   ├── README.md
│   ├── notes.md
│   ├── equations.md
│   ├── implementation/
│   ├── experiments/
│   └── references.md
│
├── 2017_attention_is_all_you_need/
│   ├── README.md
│   ├── notes.md
│   ├── equations.md
│   ├── implementation/
│   ├── experiments/
│   └── references.md
│
└── ...
```

---

# Completion Criteria

A paper is considered complete only when all of the following are finished:

- Read the original paper
- Explain the motivation
- Explain the mathematical derivations
- Implement the proposed method
- Reproduce at least one experiment (when computationally feasible)
- Document observations and limitations
