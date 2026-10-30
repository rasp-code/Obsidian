---
created: 2026-10-28
updated: 2026-10-28
---
An **event** is a subset $A \subseteq \Omega$ of the [[Sample Space]]. It **occurs** if the realized [[Outcome]] $\omega$ belongs to $A$.

**Event space**: the collection $\mathcal{F}$ of subsets of $\Omega$ considered as events. It must be a $\sigma$-algebra:
- $\Omega \in \mathcal{F}$.
- Closed under complement: $A \in \mathcal{F} \Rightarrow A^c \in \mathcal{F}$.
- Closed under countable union: $A_1, A_2, \dots \in \mathcal{F} \Rightarrow \bigcup_i A_i \in \mathcal{F}$.

**Consequences**
- $\emptyset \in \mathcal{F}$.
- $\mathcal{F}$ is closed under countable intersection and set difference.
- If $\Omega$ is finite or countable, $\mathcal{F}$ is usually the power set of $\Omega$.

**Special events**
- Elementary event: $\{\omega\}$, a single outcome.
- Certain event: $\Omega$.
- Impossible event: $\emptyset$.

**Operations**
- Complement $A^c$: $A$ does not occur.
- Union $A \cup B$: $A$ or $B$ occurs.
- Intersection $A \cap B$: $A$ and $B$ both occur.
- Mutually exclusive events: $A \cap B = \emptyset$.