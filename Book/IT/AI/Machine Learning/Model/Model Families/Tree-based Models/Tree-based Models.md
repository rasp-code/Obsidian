---
created: 2026-10-23
updated: 2026-11-03
---
Models that reach an output by asking successive questions about the inputs.

## Building Block

- [[Decision Tree]]: a single sequence of questions leading to an answer

## Ensembles

Both are built by combining many trees:

- [[Random Forest]]: many independent trees, each seeing the data a bit differently, whose answers are combined by vote or average
- [[Gradient Boosted Tree]]: trees added one after another, each fixing the mistakes of the ones before