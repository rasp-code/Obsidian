---
created: 2026-10-25
updated: 2026-10-28
---
**Generation** is the [[Task]] of producing new samples that follow the same [[Probability Distribution]] as those of a [[Dataset]].

**Formulation**
- Unconditional: sample $x \sim \hat{p}(x)$.
- Conditional: sample $x \sim \hat{p}(x \mid c)$ given a condition $c$ (see [[Conditional Probability]]).

**Conditions**
- Samples are new: not copies of training examples.
- Samples are plausible: they could have been drawn from the data distribution.

**Comparison**
- [[Density Estimation]] estimates the value of $p(x)$ instead of producing samples.
