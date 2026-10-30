---
created: 2026-10-26
updated: 2026-10-28
---
A **dataset** is a finite collection of **examples** (samples) used to train, validate or test a model (see [[Data Splitting]]). It is a structured subset of [[Data]].

**Formal description**
- Unlabeled: $\mathcal{D} = \{x_i\}_{i=1}^{N}$.
- Labeled: $\mathcal{D} = \{(x_i, y_i)\}_{i=1}^{N}$, where $y_i$ is the [[Label]] of $x_i$.
- $N$ is the size of the dataset.

**Matrix form**
- With $d$ [[Feature|features]] per example, the inputs form a [[Matrix]] $X \in \mathbb{R}^{N \times d}$, one example per row.

**Assumption**
- Examples are i.i.d.: drawn [[Independence|independently]] from the same [[Probability Distribution]].
