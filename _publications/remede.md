---
title: "Decision Trees That Remember: Gradient-Based Learning of Recurrent Decision Trees with Memory"
collection: publications
category: conferences
permalink: /publication/sympol
excerpt: 'We propose ReMeDe trees, a recurrent decision tree architecture with internal memory, enabling efficient learning for sequential data through hard, axis-aligned decision rules trained via gradient descent.'
date: 2025-04-27
venue: 'New Frontiers in Associative Memory workshop at ICLR 2025'
paperurl: 'http://s-marton.github.io/files/paper_remede.pdf'
citation: 'Marton, Sascha, et al. (2025). &quot;Decision Trees That Remember: Gradient-Based Learning of Recurrent Decision Trees with Memory.&quot; <i>New Frontiers in Associative Memory workshop at ICLR 2025</i>. 1(1).'
---

Neural architectures such as Recurrent Neural Networks (RNNs), Transformers, and State-Space Models have shown great success in handling sequential data by learning temporal dependencies. Decision Trees (DTs), on the other hand, remain a widely used class of models for structured tabular data but are typically not designed to capture sequential patterns directly. Instead, DT-based approaches for time-series data often rely on feature engineering, such as manually incorporating lag features, which can be suboptimal for capturing complex temporal dependencies. To address this limitation, we introduce ReMeDe Trees, a novel recurrent decision tree architecture that integrates an internal memory mechanism, similar to RNNs, to learn long-term dependencies in sequential data. Our model learns hard, axis-aligned decision rules for both output generation and state updates, optimizing them efficiently via gradient descent. We provide a proof-of-concept study on synthetic benchmarks to demonstrate the effectiveness of our approach.
