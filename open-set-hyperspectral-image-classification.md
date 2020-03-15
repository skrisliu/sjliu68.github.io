---
layout: home2
permalink: /open-set-hyperspectral-image-classification/
title: Open Set Hyperspectral Image Classification
tags: [project]
modified: 15-3-2020
comments: false
---

Authors: Shengjie Liu, Qian Shi

Emails: liusj@hku.hk, shixi5@mail.sysu.edu.cn
  
### Overview
Code and supporting data coming soon ...

### Abstract
Current hyperspectral image classification is regarded as a close set problem (no novel class in the unseen data).
This assumption is too strict for real-world applications. Often, novel classes are left out when constructing the classification
system. The close nature forces a model to assign a label given
a new instance and might lead to overestimation of known
land covers (e.g., crop areas). We here introduce open set
hyperspectral image classification, where novel classes might exist
and the machine should identify them. To achieve the goal, a
multitask network that simultaneously conducting classification
and reconstruction is proposed. The reconstructed data are
compared with the original data; those failed to be reconstructed
are considered as novel, based on the assumption that they are not
well presented in the latent features due to the lack of labels. The
extreme value theory is adopted to estimate the distribution of
unknown data, where two strategies, full-class tail and classwise
tail are proposed under few-shot context and sufficient training
samples. We tested the proposed method on three hyperspectral
datasets and show its ability to precisely quantify the area of
individual land cover. From close set to open set, hyperspectral
image classification can be more accurate in estimating land cover
area, especially when the classification system fails to fully cover
the categories of ground targets, which is often the case in the
real and open world.

