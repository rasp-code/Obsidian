---
created: 2026-10-27
updated: 2026-10-28
---
A **tensor** is a multidimensional array of numbers, generalizing the [[Vector]] and the [[Matrix]] to an arbitrary number of axes.

The **order** (or rank) of a tensor is its number of axes, and its **shape** is the size along each axis.

| Order | Object              | Example shape |
|---|---|---|
| 0 | [[Scalar]]          | $()$ |
| 1 | [[Vector]]          | $(n)$ |
| 2 | [[Matrix]]          | $(m, n)$ |
| 3+ | Higher-order tensor | $(d_1, d_2, d_3, \dots)$ |

An element is accessed with one index per axis: $T_{i_1 i_2 \dots i_k}$.