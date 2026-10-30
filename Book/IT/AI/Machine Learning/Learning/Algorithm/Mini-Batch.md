---
created: 2026-10-27
updated: 2026-10-28
---
A **mini-batch** is a [[Batch]] of size $B$ with $1 < B < N$: a subset of the training [[Dataset]] used to compute one parameter update.

**Construction**
- The dataset is shuffled, then split into consecutive subsets of $B$ examples, at each [[Epoch]].

**Properties**
- If drawn uniformly at random, its average gradient is an unbiased estimate of the full gradient: $\mathbb{E}[g_B] = \nabla J$ (see [[Expectation]], [[Gradient]]).
- The [[Variance]] of this estimate decreases as $B$ increases.
