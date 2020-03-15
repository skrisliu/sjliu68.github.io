---
layout: home2
permalink: /multitask-deep-learning-hyperspectral-image-classification/
title: Multitask Deep Learning With Spectral Knowledge for Hyperspectral Image Classification
tags: [project]
modified: 15-3-2020
comments: false
---

Authors: Shengjie Liu, Qian Shi

Emails: liusj@hku.hk, shixi5@mail.sysu.edu.cn


### Abstract
In this letter, we propose a multitask deep learning method for the classification of multiple hyperspectral data in a single training. Deep learning models have achieved promising results on hyperspectral image classification, but their performance highly relies on sufficient labeled samples that are scarce on hyperspectral images. However, samples from multiple data sets might be sufficient to train one deep learning model, thereby improving its performance. To do so, we trained an identical feature extractor for all data, and the extracted features were fed into corresponding softmax classifiers. Spectral knowledge was introduced to ensure that the shared features were similar across domains. Four hyperspectral data sets were used in the experiments. We achieved higher classification accuracies on three data sets (Pavia University, Pavia Center, and Indian Pines) and competitive results on the Salinas Valley data compared with the baseline. Spectral knowledge was useful to prevent the deep network from overfitting when the data shared similar spectral response. The proposed method tested on two deep CNNs successfully shows its ability to utilize samples from multiple data sets and to enhance networks' performance.

