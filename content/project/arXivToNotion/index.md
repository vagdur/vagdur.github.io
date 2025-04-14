---
title: AI-enabled paper import from arXiv to Notion
date: 2022-06-12
tags:
  - machine learning
  - data processing
---

A constant problem in most scientists' lives is keeping up with interesting new papers in their area. One classic "solution" to this is the arXiv digest emails -- every morning, you get an email with a list of the titles and abstracts of all the papers published in the areas of your choice.

Of course, of these, maybe one or two is interesting, and so you spend a lot of time sifting through papers that are utterly irrelevant to you. Then, for the ones that were interesting, you try to add them to some list of things you want to read to keep track of them -- and all too often that system is just an endless list of open tabs that you will get to "some day".

[This project](https://github.com/vagdur/arXivToNotion) offers an improved solution to both these problems. Instead of getting the arXiv email, you can directly import all those papers into a Notion database, where you can then sort them according to tags or projects or however you like, and never lose them all because Chrome crashed. It also offers a simple AI recommender algorithm that attempts to sort the papers by how similar they are to things you have found interesting in the past, automating away some of the first sieving of the data.

There are still some more features I would like to add to this: I want to improve the recommender algorithm for it, and create a simple way to set this up to run automatically in the cloud for you, instead of having to manually trigger it each morning.

<!--more-->
