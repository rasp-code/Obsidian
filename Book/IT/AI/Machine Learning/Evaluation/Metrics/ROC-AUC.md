---
created: 2026-10-28
updated: 2026-10-28
---
**ROC-AUC** is the area under the ROC curve: it measures how well the scores of a classifier separate positives from negatives, over all decision thresholds.

**ROC curve**
- True positive rate ([[Recall]]) against false positive rate, as the threshold varies:
$$\mathrm{TPR} = \frac{TP}{TP + FN}, \qquad \mathrm{FPR} = \frac{FP}{FP + TN}$$

**AUC**
$$\mathrm{AUC} = P\big(s(x^+) > s(x^-)\big)$$
- Probability that a random positive gets a higher score than a random negative.
- $1$: perfect separation. $0.5$: random scores.

**Properties**
- Independent of the threshold: only the order of the scores matters.
