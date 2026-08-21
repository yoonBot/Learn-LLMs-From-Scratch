# Learning & Research Roadmap

This roadmap defines the progression of this repository from mathematical and programming foundations to implementing modern Large Language Models and reproducing research papers.

The focus is not only on understanding concepts, but also on implementing them, validating them experimentally, and eventually extending published ideas.

---

# Phase 0 — Foundations

Before building language models, develop the mathematical and programming background required to understand modern deep learning systems.

## Mathematics

### Calculus

Topics:

- Limits
- Derivatives
- Partial derivatives
- Chain rule
- Gradients
- Jacobians
- Hessians
- Taylor series
- Multivariable optimization

Goal:

Understand the calculus behind backpropagation and optimization.

Status:

`Planned / In Progress / Completed`

---

### Linear Algebra

Topics:

- Vectors
- Matrices
- Matrix multiplication
- Linear transformations
- Vector spaces
- Basis and dimension
- Orthogonality
- Eigenvalues and eigenvectors
- Singular Value Decomposition
- Norms

Goal:

Understand how neural networks represent and transform high-dimensional data.

---

### Probability & Statistics

Topics:

- Random variables
- Probability distributions
- Expectation
- Variance
- Covariance
- Conditional probability
- Bayes' theorem
- Maximum likelihood estimation
- Sampling

Goal:

Understand probabilistic modeling, loss functions, evaluation, and uncertainty.

---

### Information Theory

Topics:

- Entropy
- Cross-entropy
- KL divergence
- Mutual information
- Perplexity

Goal:

Understand the information-theoretic quantities used throughout language modeling.

---

### Optimization

Topics:

- Gradient descent
- Stochastic gradient descent
- Momentum
- Adam
- Learning-rate schedules
- Convexity
- Constrained optimization
- Numerical optimization

Goal:

Understand how neural networks are trained and why optimization algorithms behave differently.

---

## Programming

### Python

Topics:

- Core Python
- Functions
- Classes
- Modules
- Iterators
- Generators
- Type hints
- File I/O
- Testing
- Debugging

Goal:

Write clean, readable, reusable research code.

---

### Scientific Python

Topics:

- NumPy
- SciPy
- Pandas
- Matplotlib
- Jupyter

Goal:

Become comfortable manipulating numerical data and running experiments.

---

### PyTorch

Topics:

- Tensors
- Broadcasting
- Autograd
- `nn.Module`
- Datasets
- DataLoaders
- Optimizers
- Training loops
- Checkpoints
- GPU training
- Mixed precision

Goal:

Implement and train neural networks without relying entirely on high-level libraries.

---

# Phase 1 — Neural Network Foundations

Build the components required before studying transformers.

## Feedforward Neural Networks

Implement:

- Linear layers
- Activation functions
- Loss functions
- Backpropagation
- Weight initialization
- Training loop

Experiments:

- Compare activation functions
- Compare initialization strategies
- Study overfitting and regularization

---

## Optimization

Implement:

- SGD
- Momentum
- RMSProp
- Adam

Experiments:

- Compare convergence speed
- Compare learning-rate sensitivity
- Visualize training dynamics

---

## Sequence Models

Study and implement:

- Recurrent Neural Networks
- LSTM
- GRU
- Sequence-to-sequence models

Goal:

Understand the limitations that motivated attention and transformers.

---

# Phase 2 — NLP Foundations

## Text Processing

Topics:

- Corpus preparation
- Vocabulary construction
- Token IDs
- Unknown tokens
- Special tokens

---

## Tokenization

Implement:

- Word-level tokenization
- Character-level tokenization
- Byte-level tokenization
- Byte Pair Encoding

Later study:

- WordPiece
- SentencePiece
- Modern tokenizer pipelines

Goal:

Understand exactly how raw text becomes model input.

---

## Embeddings

Implement:

- One-hot representations
- Embedding lookup
- Learned token embeddings
- Positional embeddings

Study:

- Word2Vec
- GloVe

Goal:

Understand how discrete tokens become vectors.

---

# Phase 3 — Attention

## Self-Attention

Implement from scratch:

- Query
- Key
- Value projections
- Scaled dot-product attention
- Attention masks
- Causal masking

Key equation:

\[
\text{Attention}(Q,K,V)
=
\text{softmax}
\left(
\frac{QK^T}{\sqrt{d_k}}
\right)V
\]

Goal:

Understand every matrix operation and tensor shape involved.

---

## Multi-Head Attention

Implement:

- Multiple attention heads
- Head concatenation
- Output projection

Experiments:

- Compare different numbers of heads
- Visualize attention maps
- Measure computational cost

---

# Phase 4 — Transformers

## Transformer Components

Implement:

- Multi-head attention
- Feed-forward network
- Layer normalization
- Residual connections
- Positional encoding
- Dropout

---

## Transformer Encoder

Build the encoder architecture used in the original Transformer.

---

## Transformer Decoder

Build:

- Masked self-attention
- Cross-attention
- Autoregressive decoding

---

## Full Transformer

Reproduce the architecture from:

**Attention Is All You Need**

Goals:

- Read the paper
- Explain every major equation
- Implement the model
- Train a smaller-scale version
- Compare results with expected behavior

---

# Phase 5 — GPT From Scratch

Build a decoder-only language model from individual components.

## Architecture

Implement:

- Token embeddings
- Positional embeddings
- Causal self-attention
- Multi-head attention
- Feed-forward blocks
- Residual connections
- Layer normalization
- Language-modeling head

---

## Training

Implement:

- Dataset pipeline
- Context windows
- Next-token prediction
- Cross-entropy loss
- AdamW
- Gradient clipping
- Learning-rate scheduling
- Checkpointing

---

## Inference

Implement:

- Greedy decoding
- Temperature sampling
- Top-k sampling
- Top-p sampling

Goal:

Train and generate text using a complete GPT-style language model built from scratch.

---

# Phase 6 — Modern LLM Components

Move beyond the original Transformer and GPT architectures.

## Rotary Position Embeddings

Implement and study:

- RoPE
- Relative positional information
- Long-context implications

---

## RMSNorm

Compare:

- LayerNorm
- RMSNorm

Experiments:

- Training stability
- Runtime
- Model quality

---

## SwiGLU

Implement:

- GLU
- SwiGLU

Compare against standard Transformer feed-forward networks.

---

## Attention Variants

Study and implement:

- Multi-Query Attention
- Grouped-Query Attention
- Sliding-window attention

---

## KV Cache

Implement:

- Key-value caching
- Autoregressive decoding optimization

Benchmark:

- Memory usage
- Generation speed

---

## Mixture-of-Experts

Study:

- Sparse expert routing
- Expert capacity
- Load balancing

Implement a small MoE Transformer.

---

# Phase 7 — Models From Scratch

## GPT-2

Goals:

- Read the paper
- Recreate the architecture
- Load or reproduce compatible weights where practical
- Compare implementation with published architecture

---

## Llama

Study and implement:

- RMSNorm
- RoPE
- SwiGLU
- Grouped-query attention
- Decoder-only architecture

Goal:

Build a small Llama-style model from scratch.

---

## Small Mixture-of-Experts Model

Build a compact MoE language model inspired by modern architectures.

---

# Phase 8 — Research Paper Roadmap

## Early Representation Learning

### Word2Vec

Paper goals:

- Understand the objective
- Implement Skip-gram
- Implement negative sampling

---

### GloVe

Paper goals:

- Understand co-occurrence statistics
- Implement the objective
- Compare with Word2Vec

---

## Sequence Modeling

### Sequence to Sequence Learning with Neural Networks

Goals:

- Understand encoder-decoder modeling
- Reproduce a small sequence-to-sequence experiment

---

### Neural Machine Translation by Jointly Learning to Align and Translate

Goals:

- Understand additive attention
- Implement attention
- Compare with vanilla seq2seq

---

## Transformer Era

### Attention Is All You Need

Goals:

- Explain every architectural component
- Reproduce a small Transformer
- Compare attention variants

---

### GPT

Goals:

- Understand decoder-only pretraining
- Implement the architecture
- Analyze pretraining objectives

---

### BERT

Goals:

- Understand masked language modeling
- Understand bidirectional representations
- Compare encoder-only and decoder-only architectures

---

### GPT-2

Goals:

- Study scaling
- Recreate the architecture
- Train a smaller version

---

### GPT-3

Goals:

- Study scaling behavior
- Few-shot and in-context learning
- Analyze architecture and training setup

A full-scale reproduction is not expected due to computational requirements.

---

# Phase 9 — Modern LLM Research

Study architectures and techniques used in modern frontier models.

## Llama Family

Topics:

- Architecture changes
- Scaling
- Tokenization
- Training efficiency

---

## Mistral

Topics:

- Sliding-window attention
- Grouped-query attention

---

## Mixtral

Topics:

- Sparse Mixture-of-Experts
- Routing
- Expert utilization

---

## DeepSeek

Topics may include:

- Mixture-of-Experts
- Multi-head latent attention
- Training efficiency
- Reasoning-oriented post-training
- Reinforcement learning

For large models, reproduction will focus on architectural components and small-scale experiments rather than full-scale training.

---

# Phase 10 — Research Reproduction

For each selected research paper:

1. Read the paper.
2. Identify the main contribution.
3. Rewrite the important equations.
4. Implement the method from scratch.
5. Reproduce a feasible subset of the original experiments.
6. Compare results.
7. Document discrepancies.
8. Analyze limitations.
9. Modify one component.
10. Run an original experiment.

Each reproduction should contain:

```text
paper_name/
├── README.md
├── paper_notes.md
├── equations.md
├── implementation/
├── configs/
├── experiments/
├── results/
└── references.md
```

---

# Phase 11 — Original Experiments

The final stage is to move from reproduction to research.

Possible experiments include:

- Comparing positional encoding methods
- Attention head ablations
- RoPE scaling experiments
- LayerNorm vs RMSNorm
- GELU vs SwiGLU
- AdamW vs alternative optimizers
- Context-length scaling
- Tokenizer comparisons
- KV-cache optimizations
- Grouped-query attention experiments
- Mixture-of-Experts routing experiments

Each experiment should contain:

- Hypothesis
- Methodology
- Experimental setup
- Baseline
- Metrics
- Results
- Analysis
- Limitations
- Conclusion

---

# Definition of Completion

A topic is considered **completed** only when I can:

- Explain the concept without relying on a library abstraction.
- Derive or explain the important equations.
- Implement the concept in PyTorch.
- Test the implementation.
- Explain tensor dimensions and computational complexity.
- Connect the concept to relevant research papers.

A research paper is considered **reproduced** when I can:

- Explain the paper's central contribution.
- Implement the relevant architecture or algorithm.
- Reproduce at least one meaningful experiment where computationally feasible.
- Compare my results with the published results.
- Explain any significant differences.

---

# Final Objective

The long-term objective of this repository is to progress from:

```text
Learn
  ↓
Understand
  ↓
Implement
  ↓
Reproduce
  ↓
Experiment
  ↓
Research
```

The repository is complete only when it evolves beyond reproducing existing work and begins documenting original experiments and research ideas.
