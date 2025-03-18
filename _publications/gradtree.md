---
title: "GradTree: Learning Axis-Aligned Decision Trees with Gradient Descent"
collection: publications
category: conferences
permalink: /publication/gradtree
excerpt: 'A novel approach for learning hard, axis-aligned decision trees with gradient descent.'
date: 2024-03-24
venue: 'AAAI Conference on Artificial Intelligence'
slidesurl: 'http://s-marton.github.io/files/poster_gradtree.pdf'
paperurl: 'http://s-marton.github.io/files/paper_gradtree.pdf'
citation: 'Marton, Sascha, et al. (2024). &quot;GRANDE: Gradient-Based Decision Tree Ensembles for Tabular Data.&quot; <i>Proceedings of the AAAI Conference on Artificial Intelligence</i>. 38(13).'
---

Decision Trees (DTs) are commonly used for many machine learning tasks due to their high degree of interpretability. However, learning a DT from data is a difficult optimization problem, as it is non-convex and non-differentiable. Therefore, common approaches learn DTs using a greedy growth algorithm that minimizes the impurity locally at each internal node. Unfortunately, this greedy procedure can lead to inaccurate trees. In this paper, we present a novel approach for learning hard, axis-aligned DTs with gradient descent. The proposed method uses backpropagation with a straight-through operator on a dense DT representation, to jointly optimize all tree parameters. Our approach outperforms existing methods on binary classification benchmarks and achieves competitive results for multi-class tasks. The implementation is available under: https://github.com/s-marton/GradTree
