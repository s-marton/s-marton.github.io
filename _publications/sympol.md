---
title: "Mitigating Information Loss in Tree-Based Reinforcement Learning via Direct Optimization"
collection: publications
category: conferences
permalink: /publication/sympol
excerpt: 'We propose a novel method for symbolic RL that enables end-to-end gradient-based learning of interpretable, axis-aligned decision trees, combining policy gradient optimization with symbolic decision-making.'
date: 2025-04-28
venue: 'International Conference on Learning Representations **(Spotlight)**'
slidesurl: 'http://s-marton.github.io/files/poster_sympol.pdf'
paperurl: 'http://s-marton.github.io/files/paper_sympol.pdf'
citation: 'Marton, Sascha. (2025). &quot;Mitigating Information Loss in Tree-Based Reinforcement Learning via Direct Optimization.&quot; <i>arXiv</i>. 1(1).'
---

Reinforcement learning (RL) has seen significant success across various domains, but its adoption is often limited by the black-box nature of neural network policies, making them difficult to interpret. In contrast, symbolic policies allow representing decision-making strategies in a compact and interpretable way. However, learning symbolic policies directly within on-policy methods remains challenging. In this paper, we introduce SYMPOL, a novel method for SYMbolic tree-based on-POLicy RL. SYMPOL employs a tree-based model integrated with a policy gradient method, enabling the agent to learn and adapt its actions while maintaining a high level of interpretability. We evaluate SYMPOL on a set of benchmark RL tasks, demonstrating its superiority over alternative tree-based RL approaches in terms of performance and interpretability. Unlike existing methods, it enables gradient-based, end-to-end learning of interpretable, axis-aligned decision trees within standard on-policy RL algorithms. Therefore, SYMPOL can become the foundation for a new class of interpretable RL based on decision trees. Our implementation is available under: https://github.com/s-marton/sympol
