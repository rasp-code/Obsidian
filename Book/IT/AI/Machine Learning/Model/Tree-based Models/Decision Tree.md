---
created: 2026-10-22
updated: 2026-10-28
---
A **decision tree** is a [[Model]] that predicts by applying a sequence of tests on features, from the root to a leaf.

**Structure**
- Internal node: a test on one feature, $x_j \leq s$.
- Branch: an outcome of the test.
- Leaf: a prediction (majority class, or mean value).

**Training** (greedy, top-down)
- At each node, choose the split that most decreases the impurity: Gini index $1 - \sum_k p_k^2$ or [[Entropy]] for classification, [[Variance]] for regression.
- Stop at a maximum depth, a minimum number of examples, or a pure node.

**Properties**
- Decision boundaries are axis-aligned and the prediction is piecewise constant.
- Deep trees overfit (high variance).
