---
created: 2026-10-27
updated: 2026-10-28
---
A **batch** is a group of examples of a [[Dataset]] processed together to compute one update of the model parameters.

**Batch size**
- Denoted $B$, with $1 \leq B \leq N$, where $N$ is the size of the dataset.
- $B = N$: **full batch**.
- $1 < B < N$: [[Mini-Batch]].

**Computation**
- The loss is the average of the [[Loss Function]] over the examples of the batch.
- The [[Gradient]] of this average is used to update the parameters.

**Properties**
- A larger batch gives a gradient estimate with lower [[Variance]], at a higher cost per update.
