
---
title: "Self-supervised Learning for Small Shot COVID-19 Classification"
date: 2021-10-05
authors:
  - Yujie Zhu
summary: "Recently, COVID-19 has become one of the most severe and widespread diseases with an increasing number of infections and deaths. An accurate and high-speed automatic classifier will increase the efficiency of diagnosis and reduce fatigue misdiagnosis. Given the contradiction that many previous classifiers require a large amount of data for training while it is difficult to collect the medical images of COVID-19 with labels, we propose a classification model based on self-supervised learning and transfer learning, which uses rotation and division as labels and then transfers the parameters to the classifier. It solves the overfitting problem caused by insufficient data set and improves the accuracy by nearly 30%."
tags: [Machine Learning, Deep Learning, COVID-19]
url_custom: "https://dl.acm.org/doi/abs/10.1145/3473465.3473472"
url_custom_name: "Link"
image:
  filename: "featured.png"
  preview_only: false
sharing: false
---

## Abstract

Recently, COVID-19 has become one of the most severe and widespread diseases with an increasing number of infections and deaths. An accurate and high-speed automatic classifier will increase the efficiency of diagnosis and reduce fatigue misdiagnosis. Given the contradiction that many previous classifiers require a large amount of data for training while it is difficult to collect the medical images of COVID-19 with labels, we propose a classification model based on self-supervised learning and transfer learning, which uses rotation and division as labels and then transfers the parameters to the classifier. It solves the overfitting problem caused by insufficient data set and improves the accuracy by nearly 30%.

---

## Links

- [📄 PDF](Self.pdf)
- [🔗 Link to Publisher](https://dl.acm.org/doi/abs/10.1145/3473465.3473472)


---
title: "CLIP-Guided Label-Free Discriminative Region Scoring for Fine-Grained Classification"
date: 2026-07-15
authors:
  - Yujie Zhu
summary: "Recent vision models such as CLIP and SAM enable training-free segmentation and semantic encoding for fine-grained classification. A common approach is to compare the representations of segmented image regions with the text prompt embeddings of the corresponding labels. However, it remains unclear how different local regions and CLIP-based scoring strategies affect the selection of discriminative evidence, especially when ground-truth labels are unavailable. In this paper, we propose a unified CLIP-guided label-free region scoring framework for fine-grained classification. The framework evaluates cosine similarity-based, margin-based, and entropy-based scoring strategies using both SAM-generated masks and random crops, and introduces two label-free pseudo-label variants based on global image embeddings and local region embeddings. We conduct experiments on five fine-grained classification datasets to systematically compare different region generation methods and scoring strategies. The results show that Soft Negative Margin scoring achieves the strongest performance, and pseudo-label scoring closely approximates true-label performance. Although SAM produces semantically meaningful masks, random-crop-based pseudo-label scoring consistently outperforms SAM-based scoring across all datasets, suggesting that random crops preserve surrounding information and provide more stable semantic context when pseudo-labels are noisy. In addition, SAM masks benefit from aggregating embeddings from all regions, whereas random crops tend to perform better with a smaller top-k subset. These findings provide new insights for fine-grained classification."
tags: [Fine-Grained Classification, Vision-Language Models, Label-Free Region Scoring]
url_custom: "https://arxiv.org/abs/2607.13437"
url_custom_name: "Link"
image:
  filename: "featured.png"
  preview_only: false
sharing: false
---

## Abstract

Recent vision models such as CLIP and SAM enable training-free segmentation and semantic encoding for fine-grained classification. A common approach is to compare the representations of segmented image regions with the text prompt embeddings of the corresponding labels. However, it remains unclear how different local regions and CLIP-based scoring strategies affect the selection of discriminative evidence, especially when ground-truth labels are unavailable. In this paper, we propose a unified CLIP-guided label-free region scoring framework for fine-grained classification. The framework evaluates cosine similarity-based, margin-based, and entropy-based scoring strategies using both SAM-generated masks and random crops, and introduces two label-free pseudo-label variants based on global image embeddings and local region embeddings. We conduct experiments on five fine-grained classification datasets to systematically compare different region generation methods and scoring strategies. The results show that Soft Negative Margin scoring achieves the strongest performance, and pseudo-label scoring closely approximates true-label performance. Although SAM produces semantically meaningful masks, random-crop-based pseudo-label scoring consistently outperforms SAM-based scoring across all datasets, suggesting that random crops preserve surrounding information and provide more stable semantic context when pseudo-labels are noisy. In addition, SAM masks benefit from aggregating embeddings from all regions, whereas random crops tend to perform better with a smaller top-k subset. These findings provide new insights for fine-grained classification.

---

## Links

- [📄 PDF](CLIP_paper.pdf)
- [🔗 Link to Publisher](https://arxiv.org/abs/2607.13437)


