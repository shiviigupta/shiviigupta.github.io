---
layout: page
title: Conditional Point Cloud Generation
description: Project for Visual Learning and Recognition (16-824), CMU
img: 
importance: 4
category: projects
related_publications: false
pdf: https://drive.google.com/file/d/1O7YgiNW8SUSfWuVNAM1xwSci9ZJ8TaB3/view?usp=sharing
---
<style>
.responsive-wrap iframe{ max-width: 100%;}
</style>

Fall 2023 <br>

## **Project Overview**
Relevant Links: <br>
[Point-E](https://openai.com/index/point-e/) <br>
[ControlNet](https://arxiv.org/abs/2302.05543) <br>
[Wonder3D](https://arxiv.org/abs/2310.15008)

- Developed a model for generating point clouds from text prompts and Canny edge images using ControlNet integrated with a fine-tuned stable diffusion framework, achieving P-IS scores comparable to leading single modality baselines
- Optimized Stable Diffusion by implementing low-rank adaptation resulting in cleaner intermediate 2D images, feeding them to a Wonder-3D model to generate 3D meshes, subsequently sampled into point clouds

<div align="center"><img src="/assets/img/vlr.png" alt="flowchart" width="100%">
<p align="center">
Model Workflow
</p>
</div>

---

## **Project Resources**
[Presentation Slides](https://docs.google.com/presentation/d/1VhCdML46yQwvAxJ1HVQW8EafTcHLy5YPXkr9JcBsZEw/edit#slide=id.p) <br>
[Final Report](https://drive.google.com/file/d/1O7YgiNW8SUSfWuVNAM1xwSci9ZJ8TaB3/view?usp=sharing)