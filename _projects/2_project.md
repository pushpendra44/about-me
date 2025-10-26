---
layout: page
title: Project 2
description: Choice-Based Transportation Network Design
img: assets/img/project 2.jpeg
importance: 2
category: work
giscus_comments: true
---

Network design is a well-known problem in transportation systems. Most of the existing transportation network design studies treat customer demand as exogenous. In reality, demand is impacted by the level of service, which is itself determined by the network design. A network that carries the passengers/goods from origin to destination with a lower travel time is expected to attract a higher demand. Thus, optimal network design affects and is affected by demand. Capturing this two-way relationship requires modeling endogenous customer choice, significantly increasing the problem complexity. We formulate a mixed-integer non-convex optimization model for network design that embeds a discrete choice customer demand model within it. Integrality arises from arc and path selection variables which are binary, while non-convexity stems from embedded choice models such as the logit model. We propose a general and compact formulation to represent this class of problems.

We propose the Reweighted Iterative Partial Penalty L1-norm minimization (RIPPL) heuristic, which iteratively updates variable-wise penalty weights to better approximate the L0-norm through adaptive, partial penalties. By selectively penalizing small variable magnitudes, RIPPL efficiently promotes sparsity and ensures reliable convergence. This targeted reweighting outperforms standard L1 minimization, enhancing both solution quality and scalability.

Extensive experiments on real-world case studies and simulated networks validate our approach, demonstrating significantly faster runtimes and up to a 74.43% improvement in optimality gaps over state-of-the-art methods. Our solution’s scalability enables results within just 3.12% of the optimal solution for large instances.
