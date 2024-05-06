# Adaptive Token Dictionary

This repository is an official implementation of the paper "Transcending the Limit of Local Window: Advanced Super-Resolution Transformer with Adaptive Token Dictionary", CVPR, 2024.

[[Arxiv](https://arxiv.org/abs/2401.08209)] [[visual results](https://drive.google.com/drive/folders/1HwEbAGU6WEw9ZGbFdt__BOJo_5DKflEb?usp=sharing)] [[pretrained models](https://drive.google.com/drive/folders/1D3BvTS1xBcaU1mp50k3pBzUWb7qjRvmB?usp=sharing)]

By Leheng Zhang, Yawei Li, Xingyu Zhou, Xiaorui Zhao, and Shuhang Gu.

> **Abstract:** Single Image Super-Resolution is a classic computer vision problem that involves estimating high-resolution (HR) images from low-resolution (LR) ones. Although deep neural networks (DNNs), especially Transformers for super-resolution, have seen significant advancements in recent years, challenges still remain, particularly in limited receptive field caused by window-based self-attention. To address these issues, we introduce a group of auxiliary **A**daptive **T**oken **D**ictionary to SR Transformer and establish an **ATD**-SR method. The introduced token dictionary could learn prior information from training data and adapt the learned prior to specific testing image through an adaptive refinement step. The refinement strategy could not only provide global information to all input tokens but also group image tokens into categories. Based on category partitions, we further propose a category-based self-attention mechanism designed to leverage distant but similar tokens for enhancing input features. The experimental results show that our method achieves the best performance on various single image super-resolution benchmarks.
> 
> <img width="800" src="figures/tdca-acmsa.png"> 
> <img width="800" src="figures/arch.png"> 
> <br/><br/>
> <img width="800" src="figures/viscomp_076.png">



## Contents
1. [Enviroment](#environment)
1. [Fast Inference](#fast-inference)
1. [Training](#training)
1. [Testing](#testing)
1. [Results](#results)
1. [Visual Results](#visual-results)
1. [Citation](#citation)
1. [Acknowledgements](#acknowledgements)


## Environment
- Python 3.9
- PyTorch 2.0.1


```


## Results
- Classical Image Super-Resolution

<img width="800" src="figures/classical.png">

- Lightweight Image Super-Resolution

<img width="800" src="figures/lightweight.png">

## Visual Results

- Complete visual results can be downloaded from [link](https://drive.google.com/drive/folders/1HwEbAGU6WEw9ZGbFdt__BOJo_5DKflEb?usp=sharing).

<img width="800" src="figures/viscomp_027.png">
<img width="800" src="figures/viscomp_momo.png">

