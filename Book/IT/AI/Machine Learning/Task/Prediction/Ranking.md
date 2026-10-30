---
created: 2026-10-25
updated: 2026-10-28
---
**Ranking** is the [[Prediction]] task of ordering a set of items according to their relevance for a given context, such as a query.

**Formulation**
- A scoring function $s(q, d)$ gives a score to each item $d$ for a context $q$.
- The output is the ordering of the items by decreasing score.

**Properties**
- Only the relative order matters: the result is invariant to any strictly increasing transformation of the scores.

**Comparison**
- [[Regression]] and [[Classification]] predict a value or class for each item independently.
