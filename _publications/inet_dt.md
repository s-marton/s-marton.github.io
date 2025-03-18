---
title: "Explaining neural networks without access to training data"
collection: publications
category: manuscripts
permalink: /publication/inet_dt
excerpt: 'We extend Interpretation Nets (I-Nets), which interpret models without training data, to decision trees, enhancing model interpretability when data is inaccessible.'
date: 2024-01-10
venue: 'Machine Learning'
slidesurl: 'http://s-marton.github.io/files/poster_inet_dt.pdf'
paperurl: 'http://s-marton.github.io/files/paper_inet_dt.pdf'
citation: 'Marton, Sascha, et al. (2024). &quot;Explaining neural networks without access to training data.&quot; <i>Machine Learning</i>. 113(6).'
---

We consider generating explanations for neural networks in cases where the network’s training data is not accessible, for instance due to privacy or safety issues. Recently, Interpretation Nets (I-Nets) have been proposed as a sample-free approach to post-hoc, global model interpretability that does not require access to training data. They formulate interpretation as a machine learning task that maps network representations (parameters) to a representation of an interpretable function. In this paper, we extend the I-Net framework to the cases of standard and soft decision trees as surrogate models. We propose a suitable decision tree representation and design of the corresponding I-Net output layers. Furthermore, we make I-Nets applicable to real-world tasks by considering more realistic distributions when generating the I-Net’s training data. We empirically evaluate our approach against traditional global, post-hoc interpretability approaches and show that it achieves superior results when the training data is not accessible.
