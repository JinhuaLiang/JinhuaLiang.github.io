---
title: "Learning from Taxonomy: Multi-label Few-shot Classification for Everyday Sound Recognition"
excerpt: "This paper is in peer review."
permalink: /post/compactnet/
date: 2022-10-01T15:34:30-04:00
categories:
  - blog
tags:
  - few-shot learning
  - audio tagging
  - audio classification
---
<img src="/assets/images/ladprotonet.jpg" height="400px" width="600px" align="center"/>

Sound events cover hundreds of thousands categories in the real world. To extend a pretrained model to unfamiliar sound events, few-shot learning is getting an increasing number of interests these years. However, most of the existing works still restricted to single-label classification task, which is ill-suited to the practical scenario.

To overcome these drawbacks, this work firstly curates a new database named FSD-FS for multi-label few-shot audio classification. It then explores how to incorporate audio taxonomy in few-shot learning. Specifically, this work proposes label-dependent prototypical networks (LaD-protonet) to exploit parent-children relationships between labels. Plus, it applies taxonomy-aware label smoothing techniques to boost model performance. Experiments demonstrate that LaD-protonet outperforms original prototypical networks as well as other state-of-the-art methods. Moreover, its performance can be further boosted when combined with taxonomy-aware label smoothing.

See more details in the [paper](https://arxiv.org/abs/2212.08952)
If you find this paper is helpful, please cite this paper.
```
@misc{liang2022learning,
      title={Learning from Taxonomy: Multi-label Few-Shot Classification for Everyday Sound Recognition}, 
      author={Jinhua Liang and Huy Phan and Emmanouil Benetos},
      year={2022},
      eprint={2212.08952},
      archivePrefix={arXiv},
      primaryClass={cs.SD}
}
```
