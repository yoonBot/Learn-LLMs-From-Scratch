# Paper Title — Reading Notes

## Why I am reading this

**Purpose:** Foundational / coursework / research / survey / reproduction / citation trail / general interest

**Question I want this paper to answer:**

> 

**What I already know:**

> 

---

## Pass 1 — Triage

_Read the title, abstract, introduction, headings, figures, conclusion, and references. Target: 5–15 minutes._

### One-sentence summary

> This paper...

### Problem and motivation

**What problem is addressed, and why does it matter?**

> 

**What limitation of prior work motivates this paper?**

> 

### Main idea

Explain the central idea without equations.

> 

### Claimed contributions

1. 
2. 
3. 

### Evidence at a glance

What evidence is offered, and which claim is it meant to support?

> 

### Initial skepticism

Which claims, comparisons, or assumptions need closer inspection?

> 

### Decision

- [ ] Stop: the citation and takeaway are sufficient
- [ ] Continue to Pass 2: worth understanding deeply
- [ ] Continue to Pass 3: worth challenging or implementing
- [ ] Continue to Pass 4: central to my research direction

---

## Pass 2 — Understand

_Read the complete paper. Explain why the method should work instead of restating the text._

### Problem formulation

- **Input:**
- **Output:**
- **Objective:**
- **Constraints and assumptions:**

### Method in my own words

> 

### Information flow

```text
Input
  ↓
[Component]
  ↓
[Component]
  ↓
Output
```

### Key equations

Keep complete derivations in `equations.md`. Record only equations essential to the paper's argument here.

#### Equation — Name

$$
\text{equation}
$$

- **Computes:**
- **Symbols and tensor shapes:**
- **Why it is needed:**
- **Intuition:**
- **If removed or changed:**

### Experimental design

| Element | Details |
| --- | --- |
| Datasets |  |
| Models |  |
| Baselines |  |
| Metrics |  |
| Training |  |
| Hardware / compute |  |
| Evaluation protocol |  |

### Claim-to-evidence audit

| Claim | Supporting result | Convincing? | Caveat |
| --- | --- | :---: | --- |
|  |  | Yes / Partly / No |  |

**Ablation findings:**

> 

**Uncertainty or statistical significance:**

> 

### Explain-without-the-paper check

Close the paper and answer from memory:

1. What problem does it solve?
2. How does the method work?
3. Why should it work?
4. What evidence supports it?
5. Where could it fail?

**Weak areas to revisit:**

> 

---

## Pass 3 — Challenge

_Use for papers important enough to critique, derive, or implement._

### Reconstruction from memory

Sketch the architecture, algorithm, or central equation before consulting the paper again.

```text

```

**What did I miss, and why?**

> 

### Assumption audit

| Claim | Required assumption | Explicit or implicit? | How could I test it? |
| --- | --- | --- | --- |
|  |  |  |  |

### Predicted ablations

Predict outcomes before reading the paper's ablation results.

| Change | Prediction | Paper's result | Interpretation |
| --- | --- | --- | --- |
| Remove or replace component |  |  |  |

### Failure modes

- **Out-of-distribution:**
- **Data:**
- **Scale:**
- **Compute:**
- **Evaluation:**

### Critical review

- **Strongest aspect:**
- **Biggest weakness:**
- **Missing baseline or experiment:**
- **Reproducibility concern:**
- **Claim stronger than evidence:**
- **Verdict:** Strong accept / accept / weak accept / weak reject / reject
- **Rationale:**

### Smallest useful implementation

What is the minimum experiment that would demonstrate or challenge the paper's core idea?

> 

Track commands, settings, and measured outcomes in `experiments/`, `configs/`, and `results/` rather than expanding them here.

---

## Pass 4 — Extend

_Use only for work directly connected to a research direction._

### Research lineage

```text
[Predecessor]
      ↓
THIS PAPER
      ↓
[Follow-up]
      ↓
[Current approach]
```

### What remains unsolved?

1. 
2. 
3. 

### Experiment ideas

| Hypothesis | Intervention | Expected result | Why it matters | Feasible? |
| --- | --- | --- | --- | :---: |
|  |  |  |  | Yes / Maybe / No |

### Questions generated

- [ ] Does the method still work when ...?
- [ ] Can the component be replaced by ...?
- [ ] Can the cost or data requirement be reduced?
- [ ] Does the result transfer to another domain or modality?

### Cross-domain connections

- **LLMs:**
- **Speech / ASR:**
- **Vision:**
- **Multimodal systems:**
- **Reinforcement learning / agents:**
- **Other:**

---

## Final synthesis

### Three-sentence summary

- **Problem:**
- **Method:**
- **Result:**

### Durable takeaway

What should I remember six months from now?

> 

### Limitations and relevance

- **Biggest limitation:**
- **Relevance to my work:**
- **Most important follow-up:**

### Assessment

| Dimension | Score (1–5) | Reason |
| --- | :---: | --- |
| Importance |  |  |
| Difficulty |  |  |
| Clarity |  |  |
| Evidence quality |  |  |
| Reproducibility |  |  |
| Personal relevance |  |  |

**Understanding:** 0 Seen · 1 Know · 2 Explain · 3 Implement · 4 Critique · 5 Extend

### Follow-up

- **Papers:**
- **Concepts:**
- **Implementation tasks:**
- **Research ideas:**

