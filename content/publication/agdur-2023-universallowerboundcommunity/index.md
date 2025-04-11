---
title: Universal lower bound for community structure of sparse graphs
authors:
- admin
- Nina Kamčev
- Fiona Skerman
date: '2023-07-14'
publishDate: '2025-04-11T06:40:48.356320Z'
publication_types:
- article-journal
links:
- name: arXiv
  url: https://arxiv.org/abs/2307.07271
#- name: URL
#  url: https://arxiv.org/abs/2307.07271

abstract: |-
  We prove new lower bounds on the modularity of graphs. Specifically, the modularity of a graph {{< math >}}$G${{< /math >}} with average degree {{< math >}}$\bar d${{< /math >}} is {{< math >}}$\Omega(\bar{d}^{-1/2})${{< /math >}}, under some mild assumptions on the degree sequence of {{< math >}}$G${{< /math >}}. The lower bound {{< math >}}$\Omega(\bar{d}^{-1/2})${{< /math >}} applies, for instance, to graphs with a power-law degree sequence or a near-regular degree sequence.

  It has been suggested that the relatively high modularity of the Erdős-Rényi random graph {{< math >}}$G_{n,p}${{< /math >}} stems from the random fluctuations in its edge distribution, however our results imply high modularity for any graph with a degree sequence matching that typically found in {{< math >}}$G_{n,p}${{< /math >}}.

  The proof of the new lower bound relies on certain weight-balanced bisections with few cross-edges, which build on ideas of Alon [Combinatorics, Probability and Computing (1997)] and may be of independent interest.

tags:
  - community detection
  - graph bisections
  - Newman-Girvan modularity
  - power-law degree sequence
  - preferential attachment model

image:
  caption: 'A figure from the paper.'
  focal_point: ""
  preview_only: false
---

When applying community detection in practice, one of the most commonly used methods is to try to find a partition that achieves a high _modularity_. Unfortunately, this is not a statistically justified method, and so it is in general unclear how to determine if the partition one finds is actually significant, or just the product of random noise.

In this paper, we improve the best known bounds on the modularity that are agnostic to actual structure of the graph -- so, in essence, we prove that even when there is no significant community structure, there will still be a partition with non-zero modularity. While not a statistical test, this does give some way of heuristically evaluating a partition, since if it does not achieve a much better value than our bound, it is likely just detecting noise in the data.
