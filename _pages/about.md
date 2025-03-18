---
permalink: /
title: "Hey, I'm Sascha."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a  Machine Learning Researcher at the University of Mannheim in Germany, where I have been pursuing my PhD since 2019. My research is centered on advancing machine learning techniques for tabular data, with a recent focus on gradient-based decision tree learning and tree-based ensemble methods.

## Research Interests
My current work involves developing a new approach for learning hard, axis-aligned decision trees using gradient descent. This method employs backpropagation with a straight-through operator on a dense decision tree representation, allowing for the joint optimization of all tree parameters. As a result, we achieve state-of-the-art performance across various domains, including interpretable decision trees and high-performance decision tree ensembles for tabular data, as well as interpretable reinforcement learning without information loss.

My primary research interests include:
* Ensemble Methods
* Tree-Based Methods
* Deep Learning for Tabular Data
* Time-Series Forecasting
* Explainable Artificial Intelligence

## News
### 🌳🤖 Mitigating Information Loss in Tree-Based Reinforcement Learning via Direct Optimization @ ICLR 25 (Spotlight)
* Our paper was accepted for a Spotlight (Top 5%) at ICLR 25
* We propose a novel method for tree-based RL that enables end-to-end gradient-based learning of interpretable, axis-aligned decision trees, combining policy gradient optimization with symbolic decision-making.
* 🔍 What's new?
  * No more information loss – We directly optimize tree-based policies!
  * Interpretable policies – Forget black-box models; our approach keeps policies transparent & explainable!
  * No Soft Decision Trees – While soft decision trees use probabilistic splits over multiple variables, SYMPOL makes clear, deterministic decisions for better interpretability!
  * Strong performance – Our method outperforms alternative methods for learning DT policies across benchmarks!
* Explore more:
  * Read our [paper](https://openreview.net/forum?id=qpXctF2aLZ)
  * Try our [code](https://github.com/s-marton/SYMPOL)

### 🌳🧠 Decision Trees That Remember: Gradient-Based Learning of Recurrent Decision Trees with Memory @ ICLR 25 NFAM Workshop
* Our paper was accepted at the ICLR 25 Workshop on New Frontiers in Associative Memories
* We propose ReMeDe trees, a recurrent decision tree architecture with internal memory, enabling efficient learning for sequential data through hard, axis-aligned decision trees trained via gradient descent.
* 🔍 Why does this matter?
  * Captures long-term dependencies like RNNs but retains the axis-alignment and transparency of decision trees
  * Handles sequential data without relying on fixed-size memory windows or hand-crafted features
  * Trained efficiently via Backpropagation-Through-Time
* Read our [paper](https://openreview.net/forum?id=u2Hh24rxW1)

## Publication List
### First Author Publications
[Mitigating Information Loss in Tree-Based Reinforcement Learning via Direct Optimization](https://openreview.net/forum?id=qpXctF2aLZ)<br />
<u>Sascha Marton</u>, Tim Grams, Florian Vogt, Stefan Lüdtke, Christian Bartelt, Heiner Stuckenschmidt<br />
ICLR 2025 <b>(Spotlight)</b>

[Decision Trees That Remember: Gradient-Based Learning of Recurrent Decision Trees with Memory](https://openreview.net/forum?id=u2Hh24rxW1)<br />
<u>Sascha Marton</u>, Moritz Schneider, Jannik Brinkmann, Stefan Ludtke, Christian Bartelt, Heiner Stuckenschmidt<br />
ICLR 2025 Workshop on New Frontiers in Associative Memories

[GRANDE: Gradient-Based Decision Tree Ensembles for Tabular Data](https://openreview.net/forum?id=XEFWBxi075)<br />
<u>Sascha Marton</u>, Stefan Lüdtke, Christian Bartelt, Heiner Stuckenschmidt<br />
ICLR 2024

[GradTree: Learning Axis-Aligned Decision Trees with Gradient Descent](https://ojs.aaai.org/index.php/AAAI/article/view/29345)<br />
<u>Sascha Marton</u>, Stefan Lüdtke, Christian Bartelt, Heiner Stuckenschmidt<br />
AAAI 2024 <b>(Oral)</b>

[Explaining neural networks without access to training data](https://link.springer.com/article/10.1007/s10994-023-06428-4)<br />
<u>Sascha Marton</u>, Stefan Lüdtke, Christian Bartelt, Heiner Stuckenschmidt<br />
Machine Learning Journal (2024)

[Explanations for Neural Networks by Neural Network](https://www.mdpi.com/2076-3417/12/3/980)<br />
<u>Sascha Marton</u>, Stefan Lüdtke, Christian Bartelt<br />
Applied Sciences (2022)

### Further Publications
[Beyond Pixels: Enhancing LIME with Hierarchical Features and Segmentation Foundation Models](https://openreview.net/forum?id=JHs5p6nPbG)<br />
Patrick Knab, <u>Sascha Marton</u>, Christian Bartelt<br />
ICLR 2025 Workshop on Foundation Models in the Wild

[A Data-Centric Perspective on Evaluating Machine Learning Models for Tabular Data](https://openreview.net/forum?id=kWTvdSSH5W)<br />
Andrej Tschalzev, <u>Sascha Marton</u>, Stefan Lüdtke, Christian Bartelt, Heiner Stuckenschmidt<br />
NeurIPS 2024

[DCBM: Data-Efficient Visual Concept Bottleneck Models](https://arxiv.org/abs/2412.11576)<br />
Katharina Prasse, Patrick Knab, <u>Sascha Marton</u>, Christian Bartelt, Margret Keuper<br />
arXiv preprint

[Interpreting Outliers in Time Series Data through Decoding Autoencoder](https://ceur-ws.org/Vol-3761/paper3.pdf)<br />
Patrick Knab, <u>Sascha Marton</u>, Christian Bartelt, Robert Fuder<br />
ECML-PKDD 2024 Workshop on Explainable AI for Time Series and Data Streams 

[Bias mitigation for large language models using adversarial learning](https://ceur-ws.org/Vol-3523/paper11.pdf)<br />
Jasmina S Ernst, <u>Sascha Marton</u>, Jannik Brinkmann, Eduardo Vellasques, Damien Foucard, Martin Kraemer, Marian Lambert<br />
ECAI 2023 Workshop on Fairness and Bias in AI
