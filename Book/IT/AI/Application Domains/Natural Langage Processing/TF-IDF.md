---
created: 2026-09-18
updated: 2026-10-28
---
**TF-IDF** (term frequency – inverse document frequency) is a weight measuring how important a term $t$ is to a document $d$ relative to a corpus $D$ of $N$ documents.

$$\mathrm{TFIDF}(t, d, D) = \mathrm{TF}(t, d) \times \mathrm{IDF}(t, D)$$

**Term frequency**: frequency of $t$ in $d$
$$\mathrm{TF}(t, d) = \frac{f_{t,d}}{\sum_{t' \in d} f_{t',d}}$$

**Inverse document frequency**: rarity of $t$ in $D$, with $n_t$ the number of documents containing $t$
$$\mathrm{IDF}(t, D) = \log\frac{N}{n_t}$$
- Smoothed version, avoiding division by zero: $\log\dfrac{N}{n_t + 1} + 1$ (see [[Logarithm]]).

**Properties**
- The score is high when $t$ is frequent in $d$ but rare in $D$, and low when $t$ appears in most documents.
