# Diachronic-Text-Analysis
Diachronic Text Analysis: Studying  Language Evolution Over Time

This analyzes how word meanings change over time using word embeddings trained on different time periods. Embedding spaces were aligned and measurement of semantic drift using similarity, vector displacement, and nearest neighbors.


The goal of this project was to analyze semantic evolution across time using NLP techniques. Separate word embedding models for different temporal periods were trained and their vector spaces aligned to measure semantic drift quantitatively and visually.


How language changes over time.

The project is based on the distributional hypothesis: words used in similar contexts tend to have similar meanings.

NB: Since AG News does not contain explicit timestamps, synthetic temporal labels were generated to simulate diachronic conditions.


Lowercasing: normalize vocabulary

Regex cleaning: remove punctuation/noise

Tokenization: split text into words

Lemmatization: reduce inflected forms

Word2Vec: Learn vectors by predicting contextual relationships. It works because Because semantic similarity emerges from contextual co-occurrence statistics learned during prediction optimization.

Different Word2Vec models produce different coordinate systems. So vectors cannot be directly compared. Orthogonal Procrustes alignment.

Cosine similarity:orientation.
Vector shift: displacement magnitude.
Nearest words indicate semantic context. Because semantic drift becomes interpretable linguistically


high cosine similarity,moderate vector displacement.
core semantics remain relatively stable,contextual usage evolves gradually.
Semantic evolution appears gradual rather than abrupt, suggesting contextual drift rather than complete semantic replacement.

In summary:
modeled semantic evolution,
aligned temporal embedding spaces,
quantified semantic drift,
visualized linguistic change.
