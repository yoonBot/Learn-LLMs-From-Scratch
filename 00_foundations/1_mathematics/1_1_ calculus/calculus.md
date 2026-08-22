# Calculus for Large Language Models

> **Prerequisite Reference**
>
> This document summarizes the calculus required for Machine Learning, Deep Learning, and Large Language Models (LLMs).
>
> It complements—not replaces—a traditional calculus textbook by connecting mathematical concepts directly to modern AI.

---

# Overview

Calculus is the mathematical language of optimization.

Whenever a neural network minimizes a loss function, computes gradients, or updates parameters, it is using concepts from differential calculus.

The goal of this guide is to build enough mathematical intuition to understand modern LLM implementations and research papers.

---

# Why Learn Calculus?

After completing this guide, you should be able to answer:

- Why does Gradient Descent work?
- Why is the Chain Rule the foundation of Backpropagation?
- Why are gradients vectors?
- What does `loss.backward()` actually compute?
- Why is Adam based on gradients instead of Hessians?
- What do optimization equations in modern research papers mean?

---

# Learning Objectives

You should be able to

- Compute derivatives.
- Compute partial derivatives.
- Understand gradients.
- Understand Jacobians.
- Understand Hessians.
- Derive Gradient Descent.
- Explain Backpropagation mathematically.

---

# Roadmap

1. Functions
2. Limits
3. Derivatives
4. Partial Derivatives
5. Gradients
6. Chain Rule
7. Jacobians
8. Hessians
9. Taylor Series
10. Optimization
11. Backpropagation

---

# Core Concepts

## Functions

### Why it matters

Neural networks are compositions of functions.

Used in:

- Linear Layers
- Feed Forward Networks
- Attention
- Softmax

---

## Limits

Foundation of differentiation.

---

## Derivatives

Measure the instantaneous rate of change.

Used in:

- Optimization
- Loss Functions

---

## Partial Derivatives

Modern neural networks contain millions of variables.

Each parameter has its own derivative.

---

## Gradient

Vector containing every partial derivative.

Core equation:

\[
\theta
\leftarrow
\theta
-
\eta
\nabla L(\theta)
\]

---

## Chain Rule

The mathematical foundation of Backpropagation.

---

## Jacobians

Generalization of derivatives for vector-valued functions.

---

## Hessians

Describe curvature.

Usually too expensive for modern LLMs.

---

## Taylor Series

Provides local approximations used in optimization.

---

## Optimization

Topics

- Local minima
- Saddle points
- Gradient Descent

---

# Research Notation

| Symbol | Meaning |
|---------|---------|
| x | Input |
| y | Target |
| θ | Parameters |
| η | Learning Rate |
| L | Loss |
| ∇ | Gradient |
| ∂ | Partial Derivative |
| J | Jacobian |
| H | Hessian |

---

# Essential Equations

Derivative

\[
\frac{df}{dx}
\]

Gradient

\[
\nabla f
\]

Gradient Descent

\[
\theta
\leftarrow
\theta
-
\eta
\nabla L(\theta)
\]

Chain Rule

\[
\frac{dy}{dx}
=
\frac{dy}{du}
\cdot
\frac{du}{dx}
\]

---

# PyTorch Connections

| PyTorch | Mathematics |
|----------|-------------|
| loss.backward() | Chain Rule |
| optimizer.step() | Gradient Descent |
| autograd | Automatic Differentiation |

---

# Research Papers

- Attention Is All You Need
- GPT
- GPT-2
- GPT-3
- Llama
- DeepSeek

---

# Suggested Exercises

- Derive Gradient Descent.
- Differentiate Softmax.
- Derive Cross-Entropy Loss.
- Compute a Jacobian.
- Explain Backpropagation.

---

# References

Primary

- Stewart — Calculus: Early Transcendentals

Supplementary

- Mathematics for Machine Learning
- Convex Optimization

---

# Completion Criteria

You should be able to

- explain every concept,
- derive Gradient Descent,
- explain Backpropagation,
- understand optimizer equations,
- read calculus appearing in modern LLM papers.
