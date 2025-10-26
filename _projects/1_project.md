---
layout: page
title: Optimizing Shared Micromobility Service Network Design
description: with background image
img: assets/img/project 2.jpeg
importance: 1
category: work
related_publications: true
---

Shared micromobility systems (SMS), including bike and e-scooter sharing, support the shift toward sustainable urban mobility. However, their financial viability hinges on balancing capital investment and service reliability. Oversized fleets and stations waste resources, while shortages reduce customer satisfaction. This paper presents a mathematical and computational framework to optimize SMS design by aligning capacity decisions with customer demand. We formulate a mixed-integer non-convex optimization model to determine station locations, capacities, and micromobility and rebalancing vehicle fleet sizes. Our model integrates customer preferences via a discrete choice framework and captures key operational and rebalancing dynamics.

We develop an original spatial decomposition heuristic. It separates the overall model into station-location-specific models and couples operations at individual stations through iterative bilevel updates. Local updates are computationally less expensive, occur at a higher frequency, and improve station-specific solutions, whereas the global updates are computationally more expensive, occur at a lower frequency, and reset the errors accumulated over multiple local updates to drive the solution toward optimality.

Extensive experiments using real-world data show that our approach delivers near-optimal solutions, while reducing computational times by several orders of magnitude. This scalability enables system-wide optimization, serving up to 14% more demand, and generating 82% higher profitability, and 17% lower rebalancing costs than current practice. Ultimately, our comprehensive optimization formulation combined with our efficient solution approach provides bottomline improvement annually worth 8-40 million dollars to the system operator, enhances system accessibility to the customers, and reduces environmental footprint, resulting in a more profitable, accessible and sustainable micromobility system.

