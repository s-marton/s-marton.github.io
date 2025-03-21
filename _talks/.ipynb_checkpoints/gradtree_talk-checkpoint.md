---
title: "GradTree: Learning Axis-Aligned Decision Trees with Gradient Descent"
collection: talks
type: "Talk"
permalink: /talks/gradtree
venue: "Vancouver Convention Centre"
date: 2024-02-22
location: "Vancouver, Canada"
---

[Recoding of the talk can be found here](https://www.youtube.com/watch?v=GXQCvXvJ9uA)

Decision Trees (DTs) are commonly used for many machine learning tasks due to their high degree of interpretability. However, learning a DT from data is a difficult optimization problem, as it is non-convex and non-differentiable. Therefore, common approaches learn DTs using a greedy growth algorithm that minimizes the impurity locally at each internal node. Unfortunately, this greedy procedure can lead to inaccurate trees. In this paper, we present a novel approach for learning hard, axis-aligned DTs with gradient descent. The proposed method uses backpropagation with a straight-through operator on a dense DT representation, to jointly optimize all tree parameters. Our approach outperforms existing methods on binary classification benchmarks and achieves competitive results for multi-class tasks. The implementation is available under: https://github.com/s-marton/GradTree