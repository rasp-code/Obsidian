---
created: 2026-10-25
updated: 2026-10-28
---
**Anomaly detection** is the [[Structure]] task of identifying examples that deviate significantly from the rest of a [[Dataset]].

**Formulation**
- An anomaly score $s(x)$ is computed for each example; $x$ is flagged as anomalous if $s(x)$ exceeds a threshold.

**Properties**
- Anomalies are rare, and [[Label|labels]] are often absent: what counts as normal is learned from the data.
