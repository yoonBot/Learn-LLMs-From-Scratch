# Research Paper Notes

This directory contains structured reading notes, mathematical derivations, implementations, and experiment records for influential ML and LLM papers.

## Starting a new paper

1. Copy `11_papers/_templates/paper/`.
2. Rename the copy using the existing convention: `YEAR_short_title`.
3. Add the paper metadata to its `README.md`.
4. Use `summary.md` for the reading record and `equations.md` for derivations.
5. Remove optional directories that the paper does not need.
6. Add the paper to the appropriate table in `PAPERS.md`.

For a paper that only needs survey-level coverage, use `_templates/quick_notes.md` as its `summary.md`.

## Progressive reading workflow

| Pass | Goal | Recommended for |
| --- | --- | --- |
| 1 — Triage | Identify the problem, contribution, and relevance | Every paper |
| 2 — Understand | Explain the method, equations, and evidence | Relevant papers |
| 3 — Challenge | Audit assumptions, predict ablations, and critique claims | Important papers |
| 4 — Extend | Generate research questions and experiments | Research-critical papers |

The passes are an escalation path, not a form that must always be completed. Prioritize understanding over filling every field.

## File responsibilities

| Path | Purpose |
| --- | --- |
| `README.md` | Citation, status, scope, and navigation |
| `summary.md` | Reading notes, critical analysis, and synthesis |
| `equations.md` | Important derivations, shapes, and numerical checks |
| `references.md` | Predecessors, follow-ups, and supporting resources |
| `code/` | Paper-specific implementation |
| `configs/` | Reproducible experiment settings |
| `experiments/` | Experiment definitions and commands |
| `results/` | Lightweight tables, plots, and analysis |
| `notebooks/` | Exploration that has not yet become reusable code |
| `figures/` | Original or properly attributed explanatory figures |

Keep conceptual notes in `summary.md` and measured experiment outcomes in `results/`. This prevents the reading record from becoming an implementation log.

