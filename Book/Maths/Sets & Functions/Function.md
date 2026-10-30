---
created: 2026-10-28
updated: 2026-10-28
---
A **function** $f : A \to B$ associates to each element $x$ of a set $A$ exactly one element $f(x)$ of a set $B$.

**Elements**
- Domain: the set $A$ of inputs.
- Codomain: the set $B$ in which the values lie.
- Image (range): the set $f(A) = \{f(x) \mid x \in A\} \subseteq B$.
- Graph: the set of pairs $\{(x, f(x)) \mid x \in A\}$.

**Conditions**
- Every element of $A$ has an image (total).
- Every element of $A$ has exactly one image (single-valued).

**Composition**
- $(g \circ f)(x) = g(f(x))$, defined when the image of $f$ is included in the domain of $g$.
- Associative: $(h \circ g) \circ f = h \circ (g \circ f)$.

**Types**
- Injective: $f(x) = f(y) \Rightarrow x = y$.
- Surjective: every element of $B$ has at least one preimage.
- Bijective: injective and surjective.

**Inverse**
- A function $f^{-1} : B \to A$ with $f^{-1}(f(x)) = x$ and $f(f^{-1}(y)) = y$ exists if and only if $f$ is bijective.