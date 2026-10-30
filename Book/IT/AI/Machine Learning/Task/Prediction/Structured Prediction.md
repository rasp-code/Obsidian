---
created: 2026-10-25
updated: 2026-10-28
---
**Structured prediction** is the [[Prediction]] task where the [[Output]] is a structured object (sequence, tree, graph) whose components depend on each other.

**Formulation**
- A function $f : \mathcal{X} \to \mathcal{Y}$, where $\mathcal{Y}$ is a large combinatorial space of structures.
- Prediction is a search for the best-scoring structure:
$$\hat{y} = \arg\max_{y \in \mathcal{Y}} s(x, y)$$

**Properties**
- The size of $\mathcal{Y}$ grows exponentially with the size of the object: outputs cannot be enumerated.
- Predicting each component independently ignores the constraints between them.

**Comparison**
- [[Classification]] and [[Regression]] output a single class or value.
