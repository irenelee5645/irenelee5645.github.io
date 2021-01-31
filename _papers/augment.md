---
title: "Analysis of Input Pipeline Overhead for Training Image Classifiers with Data Augmentation (KSC 2020)"
collection: research
permalink: /research/augment
excerpt: ''
# date: 2020-11-23
venue: 'KSC'
# paperurl: 'https://drive.google.com/file/d/1MA4LWGUXRF5iSLmWW2ehyXMJ66W6x_hM/view?usp=sharing'
citation: 'Irene Lee (Georgia Tech), Gyewon Lee(Seoul National University), Byung-Gon Chun.'
---

### Abstract

*Image classification is a popular application of deep neural networks. Data augmentation is often used to train models for such task in order to reduce estimation error from limited number of data and to increase generalization of trained models. However, due to the non-deterministic nature of data augmentation, preprocessed data is not reusable, leaving the input pipeline overhead unavoidable for every iteration of training. In this work, we analyze the impact of input pipeline overhead on training throughput of image classification models in various hardware settings. The key observations of the experiment are that data augmentation degrades training speed, and that the degradation becomes worse as 1) the model being trained gets smaller, 2) the CPU-GPU ratio decreases, and 3) the number of augmentation layers increases.*

* [View PDF](http://irenelee5645.github.io/files/ksc.pdf)

