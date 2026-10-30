---
created: 2026-10-26
updated: 2026-10-28
---
**Classification** is the [[Prediction]] task of assigning an [[Input]] to one class among a finite set of $K$ categories.

**Formulation**
- A function $f : \mathcal{X} \to \{1, \dots, K\}$, learned from examples with class [[Label|labels]].
- The model often outputs a [[Probability Distribution]] over the classes; the predicted class is the most probable one.

**Properties**
- The **decision boundary** separates the regions of the input space assigned to different classes.

**Models**
- [[Logistic Regression]]: linear model for binary classification.

**Comparison**
- [[Regression]] predicts a continuous value.
