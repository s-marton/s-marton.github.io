---
title: "SYMPOL: Symbolic Tree-Based On-Policy Reinforcement Learning"
collection: publications
category: conferences
permalink: /publication/sympol
excerpt: 'SYMPOL integrates a symbolic tree-based architecture with PPO for interpretable, on-policy reinforcement learning, outperforming other tree-based methods.'
date: 2024-08-16
venue: 'arXiv'
slidesurl: 'http://s-marton.github.io/files/poster_sympol.pdf'
paperurl: 'http://s-marton.github.io/files/paper_sympol.pdf'
citation: 'Marton, Sascha. (2024). &quot;SYMPOL: Symbolic Tree-Based On-Policy Reinforcement Learning.&quot; <i>arXiv</i>. 1(1).'
---

Reinforcement learning (RL) has seen significant success across various domains, but its adoption is often limited by the black-box nature of neural network policies, making them difficult to interpret. In contrast, symbolic policies allow representing decision-making strategies in a compact and interpretable way. However, learning symbolic policies directly within on-policy methods remains challenging. In this paper, we introduce SYMPOL, a novel method for SYMbolic tree-based on-POLicy RL. SYMPOL employs a tree-based model integrated with a policy gradient method, enabling the agent to learn and adapt its actions while maintaining a high level of interpretability. We evaluate SYMPOL on a set of benchmark RL tasks, demonstrating its superiority over alternative tree-based RL approaches in terms of performance and interpretability. To the best of our knowledge, this is the first method, that allows a gradient-based end-to-end learning of interpretable, axis-aligned decision trees on-policy. Therefore, SYMPOL can become the foundation for a new class of interpretable RL based on decision trees. Our implementation is available under: https://github.com/s-marton/SYMPOL
