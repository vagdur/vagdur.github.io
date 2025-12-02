---
title: Quadratic Assignment Problem solver in Rust
date: 2025-12-02
tags:
  - Rust
  - Combinatorial Optimization
---

When I was planning my defence party, I might have nerded out a bit too hard on the table placements. I realized that, if I have the full data on how good it is to seat any pair of people next to each other, determining a full table placement is just a combinatorial optimization problem. Specifically, the [Quadratic Assignment Problem](https://en.wikipedia.org/wiki/Quadratic_assignment_problem).

I wasn't very happy with the R library I found for solving this problem - the placements weren't good enough. So I decided to take the opportunity to learn some Rust, and wrote [my own solver](https://github.com/vagdur/sparse-qap-solver) in Rust, with R and Python wrappers.

My method and the R qap library both use simulated annealing, but by exploiting the sparse structure often present in at least one of the two matrices, mine is able to achieve better speed and solution qualities. There is also an implementation in SciPy using a different relax-solve-project style algorithm, called Fast Approximate QAP, which is considerably faster but finds somewhat worse solutions. See the [release notes here](https://github.com/vagdur/sparse-qap-solver/releases/tag/v0.9.0) for a full benchmark comparison.
