---
title: Fixed-parameter tractability of the mixed-sign k-part minimum edge cut problem
  on sparse graphs
authors:
- admin
date: '2025-05-01'
publishDate: '2025-04-11T06:40:48.371423Z'
publication_types:
- manuscript
abstract: |-
  We show that the problem of finding a minimum edge cut separating a weighted graph into $k$ parts, where some edges are allowed to have negative weight, is fixed-parameter tractable as long as both the graph itself and the negative-weight edges are sparse. In particular, we require the negative-weight edges to have a small vertex cover, a bound on the weights, and the graph to have bounded edge cuts, in a sense we define.

  A graph class having bounded edge cuts is essentially equivalent to having uniformly bounded local edge connectivity -- so this includes graphs with bounded edge-cut width and with bounded maximum degree. We show some basic results about these graph classes that we need for our main theorem.

tags:
  - algorithms
  - graph bisections
  - graph cuts

image:
  caption: 'A figure from the paper.'
  focal_point: ""
  preview_only: false
---

When applying community detection methods such as modularity, one encounters an optimization problem of the general form "I have a collection of objects that I need to divide into bags, and for each pair there is a cost or benefit associated to putting them in the same bag". In general, this problem is very hard to solve, but for some particular instances, it is known to be easy when dividing into two bags.

In this paper, we generalize this result to any fixed number of bags, showing that the problem is tractable as long as not too many of the pairs of items have a benefit instead of a cost to being put in the same bag. This result does not directly apply to modularity optimization, because the parameters involved are large for that instance of the problem, but the research is certainly motivated by having attempted to understand the complexity of modularity optimization.

This paper was first presented at the sixth [MMiDP](https://www.umu.se/en/research/groups/discrete-mathematics/midwinter-meeting-in-discrete-probability/), and will soon be put on arXiv. 
