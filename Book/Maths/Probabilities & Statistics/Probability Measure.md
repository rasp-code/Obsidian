---
created: 2026-10-28
updated: 2026-10-28
---
A **probability measure** is a function $P : \mathcal{F} \to [0, 1]$ that assigns a probability to each [[Event]] of the event space $\mathcal{F}$ of a [[Sample Space]] $\Omega$.

**Axioms (Kolmogorov)**
- Non-negativity: $P(A) \geq 0$ for every event $A$.
- Normalization: $P(\Omega) = 1$.
- Countable additivity: for pairwise mutually exclusive events $A_1, A_2, \dots$,
$$P\Big(\bigcup_i A_i\Big) = \sum_i P(A_i)$$

**Consequences**
- $P(\emptyset) = 0$.
- $P(A^c) = 1 - P(A)$.
- If $A \subseteq B$ then $P(A) \leq P(B)$.
- $P(A \cup B) = P(A) + P(B) - P(A \cap B)$.

The triple $(\Omega, \mathcal{F}, P)$ is called a **probability space**.