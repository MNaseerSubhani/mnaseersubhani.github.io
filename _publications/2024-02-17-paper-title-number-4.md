---
title: "Learning from Scale-Invariant Examples for
Domain Adaptation in Semantic Segmentation"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is about domain adaptation in semantic segmentation.' 
date: 2020-02-17
venue: 'ECCV'
paperurl: 'https://arxiv.org/pdf/2007.14449'
citation: M.Naseer Subhani, Mohsen Ali 

---

Self-supervised learning approaches for unsupervised domain adaptation (UDA) of semantic segmentation models suffer from challenges of predicting and selecting reasonable good quality pseudo labels. In this paper, we propose a novel approach of exploiting scale-invariance property of the semantic segmentation model for self-supervised domain adaptation. Our algorithm is based on a reasonable assumption that, in general, regardless of the size of the object and stuff (given context) the semantic labeling should be unchanged. We show that this constraint is violated over the images of the target domain, and hence could be used to transfer labels in-between differently scaled patches. Specifically, we show that semantic segmentation model produces output with high entropy when presented with scaled-up patches of target domain, in comparison to when presented original size images. These scale-invariant examples are extracted from the most confident images of the target domain. Dynamic class specific entropy thresholding mechanism is presented to filter out unreliable pseudo-labels. Furthermore, we also incorporate the focal loss to tackle the problem of class imbalance in self-supervised learning. Extensive experiments have been performed, and results indicate that exploiting the scale-invariant labeling, we outperform existing self-supervised based state-of-the-art domain adaptation methods. Specifically, we achieve 1.3% and 3.8% of lead for GTA5 to Cityscapes and SYNTHIA to Cityscapes with VGG16-FCN8 baseline network.

**[Paper](https://arxiv.org/pdf/2007.14449)**
**[Code](https://github.com/MNaseerSubhani/LSE)**


