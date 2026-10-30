---
created: 2026-10-26
updated: 2026-10-28
---
**Data transformation** converts the values of [[Feature|features]] into a form better suited to a [[Model]].

**Operations**
- Scaling: bring features to a common scale. Standardization gives mean $0$ and standard deviation $1$:
$$x' = \frac{x - \mu}{\sigma}$$
- Encoding: convert categorical features into numbers. One-hot encoding creates one binary feature per category.
