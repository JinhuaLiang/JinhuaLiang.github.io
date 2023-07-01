---
title: "Channel Compression: Rethinking Information Redundancy Among Channels in CNN Architecture"
excerpt: "This paper is accepted by IEEE Access."
permalink: /post/compactnet/
date: 2020-05-01T15:34:30-04:00
categories:
  - blog
tags:
  - acoustic scene classification
  - audio classification
  - model compression and acceleration
---
<img src="/assets/images/CompactNet.jpg" height="400px" width="600px" align="center"/>

Model compression and acceleration are attracting increasing attention due to the demand for embedded devices and mobile applications. Research on efficient convolutional neural networks (CNNs) aims at removing feature redundancy by decomposing or optimizing the convolutional calculation. In this work, feature redundancy is assumed to exist among channels in CNN architectures, which provides some leeway to boost calculation efficiency. Aiming at channel compression, a novel convolutional construction named compact convolution is proposed to embrace the progress in spatial convolution, channel grouping and pooling operation. Specifically, the depth-wise separable convolution and the point-wise interchannel operation are utilized to efficiently extract features. Different from the existing channel compression method which usually introduces considerable learnable weights, the proposed compact convolution can reduce feature redundancy with no extra parameters. With the point-wise interchannel operation, compact convolutions implicitly squeeze the channel dimension of feature maps. To explore the rules on reducing channel redundancy in neural networks, the comparison is made among different point-wise interchannel operations. Moreover, compact convolutions are extended to tackle with multiple tasks, such as acoustic scene classification, sound event detection and image classification. The extensive experiments demonstrate that our compact convolution not only exhibits high effectiveness in several multimedia tasks, but also can be efficiently implemented by benefitting from parallel computation.

See more details in the [paper](https://ieeexplore.ieee.org/document/9164969)
If you find this paper is helpful, please cite this paper.
```
@ARTICLE{9164969,
  author={Liang, Jinhua and Zhang, Tao and Feng, Guoqing},
  journal={IEEE Access}, 
  title={Channel Compression: Rethinking Information Redundancy Among Channels in CNN Architecture}, 
  year={2020},
  volume={8},
  number={},
  pages={147265-147274},
  doi={10.1109/ACCESS.2020.3015714}}
```
