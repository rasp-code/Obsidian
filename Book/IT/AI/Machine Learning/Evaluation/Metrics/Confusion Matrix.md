---
created: 2026-10-27
updated: 2026-10-28
---
A **confusion matrix** is a table that counts the predictions of a classifier against the true classes.

**Binary case**

| | Predicted positive | Predicted negative |
|---|---|---|
| **Actual positive** | TP | FN |
| **Actual negative** | FP | TN |

- TP, TN: true positives, true negatives (correct predictions).
- FP: false positive (type I error).
- FN: false negative (type II error).

**General case**
- For $K$ classes: a $K \times K$ [[Matrix]] whose entry $(i, j)$ counts examples of class $i$ predicted as $j$; the diagonal holds the correct predictions.
