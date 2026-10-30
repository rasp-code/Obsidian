---
created: 2026-10-28
updated: 2026-10-28
---
**Independence** formalizes the absence of influence between [[Event]]s or between [[Random Variable]]s, with respect to a [[Probability Measure]] $P$.

**Two events**
- $A$ and $B$ are independent if and only if $P(A \cap B) = P(A)\,P(B)$.
- If $P(B) > 0$, this is equivalent to $P(A \mid B) = P(A)$ (see [[Conditional Probability]]): knowing that $B$ occurred does not change the probability of $A$.

**Properties of two independent events**
- Symmetric: $A$ independent of $B$ implies $B$ independent of $A$.
- $A$ and $B^c$, $A^c$ and $B$, $A^c$ and $B^c$ are also independent.
- Any event is independent of $\Omega$ and of $\emptyset$.
- An event with probability $0$ or $1$ is independent of every event.

**Family of events**
- Pairwise independent: every pair $A_i, A_j$ with $i \neq j$ is independent.
- Mutually independent: for every finite subset $I$ of indices, $P\big(\bigcap_{i \in I} A_i\big) = \prod_{i \in I} P(A_i)$.
- Mutual independence implies pairwise independence; the converse is false.

**Two random variables**
- $X$ and $Y$ are independent if and only if for all measurable sets $B_1, B_2$: $P(X \in B_1,\, Y \in B_2) = P(X \in B_1)\,P(Y \in B_2)$.
- Equivalently, the events $\{X \in B_1\}$ and $\{Y \in B_2\}$ are independent for all $B_1, B_2$.
- Discrete case: $p(x, y) = p_X(x)\,p_Y(y)$.
- Continuous case: $f(x, y) = f_X(x)\,f_Y(y)$.

**Comparison with mutual exclusivity**
- Mutually exclusive events with positive probabilities are never independent, since $P(A \cap B) = 0 \neq P(A)\,P(B)$.