---
created: 2026-10-25
updated: 2026-10-28
---
**Association rule learning** is the [[Structure]] task of discovering rules $X \Rightarrow Y$ in a [[Dataset]] of transactions, meaning that the presence of the itemset $X$ tends to come with the itemset $Y$.

**Elements**
- Item: an element that can appear in a transaction.
- Itemset: a set of items.
- Transaction: the itemset of one example.
- Rule: $X \Rightarrow Y$, with $X \cap Y = \emptyset$.

**Metrics**
- Support: proportion of transactions containing both itemsets, $\mathrm{supp}(X \Rightarrow Y) = P(X \cup Y)$.
- Confidence: $\mathrm{conf}(X \Rightarrow Y) = P(Y \mid X)$ (see [[Conditional Probability]]).
- Lift: $\mathrm{lift}(X \Rightarrow Y) = \dfrac{P(Y \mid X)}{P(Y)}$.

**Properties**
- Lift $= 1$ if and only if $X$ and $Y$ are [[Independence|independent]]; $> 1$: positive association; $< 1$: negative association.
- A rule is kept if its support and confidence exceed minimum thresholds.
- A rule expresses co-occurrence, not causality.
