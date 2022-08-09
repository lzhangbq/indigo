---
title: "Image-Based Face Classification and Verification"
layout: post
date: February 2022
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

Deep Learning Course Project at CMU.


This project aims to use Convolutional Neural Networks (CNNs) to design an
end-to-end system for multi-label face classification and face verification.


My work:
- Implemented one recent baseline model [ConvNet](https://arxiv.org/pdf/2201.03545.pdf) toward the design of a vision Transformer.
- Applied data augmentation techniques to images including random augmentation, random affine. 
- Performed [Triplet loss](https://pytorch.org/docs/stable/generated/torch.nn.TripletMarginLoss.html) to model the similarities among triplets of faces on Face Verification tasks.
- Obtained over 90% in Face Classification tasks, and over 96% in Face Verification tasks. Ranked 14/354 on Kaggle Competition. 


![Screenshot](https://raw.githubusercontent.com/lzhangbq/lzhangbq.github.io/gh-pages/_posts/Face_Classification.png)
A typical Face Classification Architecture

---

![Screenshot](https://raw.githubusercontent.com/lzhangbq/lzhangbq.github.io/gh-pages/_posts/Face-Verification.png)
Face Verification Architecture


---

