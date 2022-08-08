---
title: "Paper to Poster – Directed Study"
layout: post
date: September 2021
tag: Academic
image: https://sergiokopplin.github.io/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description:
category: project
author: Liangwei Zhang
externalLink: false
---

Directed Study Project at CMU.


This project aims to create fine-tuned
poster layout annotation datasets. Moreover, we implemented the pipeline to funetune the pre-trained LayoutTransfomer Model on the poster dataset to generate reasonable lay-
outs for academic posters.

My work:
- Created a layout dataset of academic posters through [Amazon Mechanical Turk](https://www.mturk.com/) (MTurk).
- Devised bounding box annotation instructions of academic papers and annotated over 500 posters.
- Developed an end-to-end tool to generate posters
from paper.
- Finetuned the [LayoutTransformer](https://arxiv.org/abs/2006.14615) model to 
generate poster layouts.

![Screenshot](https://github.com/lzhangbq/lzhangbq.github.io/blob/gh-pages/_posts/directed-study-overview.png)

Overview Method Design for Poster Layout Generation

---
