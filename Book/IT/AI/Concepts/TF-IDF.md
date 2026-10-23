---
created: 2026-09-18
updated: 2026-09-18
---
# TF-IDF

**TF-IDF** (Term Frequency – Inverse Document Frequency) is a statistical measure that evaluates how important a word is to a document relative to a corpus. It's used to weight terms: a word that's frequent in one document but rare across the corpus gets a high score (discriminative word), while a word common everywhere (e.g. "the", "and") gets a low score.

## Formulas

**Term Frequency** — frequency of term $t$ in document $d$:
$$
TF(t,d) = \frac{f_{t,d}}{\sum_{t' \in d} f_{t',d}}
$$

**Inverse Document Frequency** — rarity of term $t$ across corpus $D$:
$$
IDF(t,D) = \log\left(\frac{N}{n_t}\right)
$$

- $N$: total number of documents
- $n_t$: number of documents containing $t$

*Smoothed variant (avoids division by zero):*
$$
IDF(t,D) = \log\left(\frac{N}{n_t + 1}\right) + 1
$$

**Final score:**
$$
TFIDF(t,d,D) = TF(t,d) \times IDF(t,D)
$$

## Key takeaways
- Score ↑ if the word is frequent **in** $d$ but rare **elsewhere**
- Score ↓ if the word is common across all documents