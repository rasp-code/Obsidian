---
created: 2026-10-26
updated: 2026-11-03
---
Predicts the probability of a class from a weighted sum of the inputs, squashed into $[0, 1]$.

**With two classes, binary logistic regression is used:**
$$p(y=1 \mid x) = \sigma(w^\top x + b)$$

with $\sigma$ the [[Sigmoid]].

**With more classes, multi-class logistic regression is used:**
$$p(y=k \mid x) = \sigma(z)_k, \quad z = (z_1, \dots, z_K), \quad z_k = w_k^\top x + b_k$$

with one set of [[Weight|weights]] $w_k$ and [[Bias|bias]] $b_k$ per class $k$, and $\sigma$ the [[SoftMax]].

