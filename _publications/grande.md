---
title: "GRANDE: Gradient-Based Decision Tree Ensembles for Tabular Data"
collection: publications
category: conferences
permalink: /publication/grande
excerpt: 'A novel ensemble method for hard, axis-aligned decision trees learned end-to-end with gradient descent.'
date: 2024-05-07
venue: 'International Conference on Learning Representations'
slidesurl: 'http://s-marton.github.io/files/poster_grande.pdf'
paperurl: 'http://s-marton.github.io/files/paper_grande.pdf'
citation: 'Marton, Sascha. (2024). &quot;GRANDE: Gradient-Based Decision Tree Ensembles for Tabular Data.&quot; <i>The Twelfth International Conference on Learning Representations</i>. 1(1).'
---

Despite the success of deep learning for text and image data, tree-based ensemble models are still state-of-the-art for machine learning with heterogeneous tabular data. However, there is a significant need for tabular-specific gradient-based methods due to their high flexibility. In this paper, we propose GRANDE, GRAdieNt-based Decision tree Ensembles, a novel approach for learning hard, axis-aligned decision tree ensembles using end-to-end gradient descent. GRANDE is based on a dense representation of tree ensembles, which affords to use backpropagation with a straight-through operator to jointly optimize all model parameters. Our method combines axis-aligned splits, which is a useful inductive bias for tabular data, with the flexibility of gradient-based optimization. Furthermore, we introduce an advanced instance-wise weighting that facilitates learning representations for both, simple and complex relations, within a single model. We conducted an extensive evaluation on a predefined benchmark with 19 classification datasets and demonstrate that our method outperforms existing gradient-boosting and deep learning frameworks on most datasets. The method is available under: https://github.com/s-marton/GRANDE
