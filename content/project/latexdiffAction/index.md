---
title: latexdiff action for GitHub repositories
date: 2025-10-10
tags:
  - Continuous Integration
  - Docker
  - LaTeX
---

From the experience of writing mathematics papers with large groups of collaborators, I know the pain of trying to keep track of what changed where. Often, the experience has been rather like trying to write a large piece of software using only Google Docs to store your code.

So, mathematics needs to learn to use git. It also needs better tooling built on top of it - such as [this project](https://github.com/vagdur/LaTeX-Paper-Template/). It is a template repository, equipped with an Action that will re-compile your LaTeX files on each commit, and run latexdiff to get a clear pdf of the diff with the previous commit. It's the kind of thing that is very basic when doing software, but for some reason very rare when doing mathematics - so I had to write it myself.
