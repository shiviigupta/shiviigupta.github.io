---
layout: page
title: Self Configuring Graph Neural Networks
description: Project for Graph Signal Processing and Geometric Learning (18-898), CMU
img: 
importance: 5
category: projects
related_publications: false
github: https://github.com/shiviigupta/self-configuring-gcn
---
<style>
.responsive-wrap iframe{ max-width: 100%;}
</style>

Fall 2023 <br>

## **Project Overview**
Relevant Links: <br>
[Reference paper](https://demalworkshop.github.io/www2021/papers/graphconvolutional.pdf)
- Introduced a novel configuration method for graph neural networks by incorporating node addition via K-means and edge reweighting through graph attention mechanism, resulting in 3% accuracy improvement on semi-supervised classification
- Conducted rigorous exploration of node and edge additions at various stages of the training pipeline, demonstrating performance comparable to existing methodologies


<div align="center"><img src="/assets/img/node_add.png" alt="flowchart" width="60%">
<p align="center">
Node Addition: Adding new nodes based on similarities of features, acting as communication centers
</p>
</div>

<div align="center"><img src="/assets/img/reweighting.png" alt="flowchart" width="60%">
<p align="center">
Edge Reweighting: Learns dependencies better
</p>
</div>

---

## **Project Resources**
[Github Repo](https://github.com/shiviigupta/self-configuring-gcn) <br>
[Presentation Slides](https://docs.google.com/presentation/d/1bN8da3-dBA4xuT2kXDnbZZP2raAQpId0lUpIEqDu8vI/edit#slide=id.p1)