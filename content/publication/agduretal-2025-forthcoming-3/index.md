---
title: Approximating temporal modularity on graphs of small underlying treewidth
authors:
- admin
- Jessica Enright
- Laura Larios-Jones
- Kitty Meeks
- Fiona Skerman
- Ella Yates
date: '2025-06-01'
publishDate: '2025-04-11T06:40:48.377319Z'
publication_types:
- manuscript
links:
- name: arXiv
  url: https://arxiv.org/abs/2507.17541
tags:
  - temporal graphs
  - community detection
  - algorithms
image:
  caption: 'A figure from the paper.'
  focal_point: ""
  preview_only: false
---

As with the other papers in my PhD, this one concerns the detection of community structure in graphs. The difference is that we notice something new about reality: Time exists. Things change over time - new connections are added to our graphs. How does this affect the problem of detecting the community structure in said graph?

A priori, one should expect that this makes it considerably harder, since time adds an entirely new dimension, and a naïve approach would have to consider every time simultaneously. However, in this paper, we demonstrate that similar guarantees for when an approximate solution can be found in fact apply also in the temporal case, if we apply some extra tricks and new approximation results.
