---
created: 2026-10-27
updated: 2026-10-28
---
An **epoch** is one complete pass over the training [[Dataset]]: each example has been used once.

**Relation to batches**
- An **iteration** (step) is one parameter update, computed on one [[Batch]].
- With batch size $B$ and $N$ examples, an epoch consists of $\lceil N / B \rceil$ iterations.

**Properties**
- Training runs for several epochs, until a stopping criterion is met.
- Examples are usually shuffled between epochs.
