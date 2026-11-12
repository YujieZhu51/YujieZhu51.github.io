---
title: "CLIP-Guided Label-Free Discriminative Region Scoring for Fine-Grained Classification"
date: 2026-07-15
authors:
  - Yujie Zhu
summary: "Recent vision models such as CLIP and SAM enable training-free approaches to fine-grained classification. However, identifying discriminative image regions without ground-truth labels remains challenging. In this paper, we propose a unified CLIP-guided label-free region scoring framework that evaluates different scoring strategies using SAM-generated masks and random crops. We conduct experiments on five fine-grained classification datasets and introduce pseudo-label strategies based on global and local image embeddings. Our results show that Soft Negative Margin scoring achieves the strongest performance, while random crops consistently outperform SAM-generated masks under pseudo-label settings, highlighting the importance of preserving semantic context in fine-grained classification."
tags: [Fine-Grained Classification, Vision-Language Models, Label-Free Region Scoring]
url_custom: "https://arxiv.org/abs/2607.13437"
url_custom_name: "Link"
image:
  filename: "CLIP.jpg"
  preview_only: false
sharing: false
---

## Abstract

Recent vision models such as CLIP and SAM enable training-free segmentation and semantic encoding for fine-grained classification. A common approach is to compare the representations of segmented image regions with the text prompt embeddings of the corresponding labels. However, it remains unclear how different local regions and CLIP-based scoring strategies affect the selection of discriminative evidence, especially when ground-truth labels are unavailable. In this paper, we propose a unified CLIP-guided label-free region scoring framework for fine-grained classification. The framework evaluates cosine similarity-based, margin-based, and entropy-based scoring strategies using both SAM-generated masks and random crops, and introduces two label-free pseudo-label variants based on global image embeddings and local region embeddings. We conduct experiments on five fine-grained classification datasets to systematically compare different region generation methods and scoring strategies. The results show that Soft Negative Margin scoring achieves the strongest performance, and pseudo-label scoring closely approximates true-label performance. Although SAM produces semantically meaningful masks, random-crop-based pseudo-label scoring consistently outperforms SAM-based scoring across all datasets, suggesting that random crops preserve surrounding information and provide more stable semantic context when pseudo-labels are noisy. In addition, SAM masks benefit from aggregating embeddings from all regions, whereas random crops tend to perform better with a smaller top-k subset. These findings provide new insights for fine-grained classification.

---

## Links

- [📄 PDF](CLIP_paper.pdf)
- [🔗 Link to Publisher](https://arxiv.org/abs/2607.13437)
