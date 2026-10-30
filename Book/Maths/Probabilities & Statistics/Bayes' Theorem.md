---
created: 2026-10-27
updated: 2026-10-28
---
**Bayes' theorem** expresses the [[Conditional Probability]] $P(A \mid B)$ in terms of the reverse conditional probability $P(B \mid A)$:

$$P(A \mid B) = \frac{P(B \mid A)\,P(A)}{P(B)}$$

**Condition**
- $P(B) > 0$ (and $P(A) > 0$ for $P(B \mid A)$ to be defined).

**Terms**
- $P(A)$: **prior**, probability of $A$ before observing $B$.
- $P(B \mid A)$: **likelihood**, probability of observing $B$ if $A$ holds.
- $P(A \mid B)$: **posterior**, probability of $A$ after observing $B$.
- $P(B)$: **evidence**, normalizing constant.

**Derivation**
- It follows from the product rule $P(A \cap B) = P(A \mid B)\,P(B) = P(B \mid A)\,P(A)$.

**Law of total probability** (to compute the evidence)
- For a partition $(A_i)$ of the [[Sample Space]] (events that are pairwise mutually exclusive and whose union is $\Omega$): $P(B) = \sum_i P(B \mid A_i)\,P(A_i)$.
- Hence $P(A_j \mid B) = \dfrac{P(B \mid A_j)\,P(A_j)}{\sum_i P(B \mid A_i)\,P(A_i)}$.