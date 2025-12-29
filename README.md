# Customize Your Visual Autoregressive Recipe with Set Autoregressive Modeling
<div align="center">

[![arXiv](https://img.shields.io/badge/arXiv%20paper-2410.10511-b31b1b)](https://arxiv.org/abs/2410.10511)&nbsp;
[![project page](https://img.shields.io/badge/Project%20page-SAR-pink)](https://poppuppy.github.io/sar.github.io/)&nbsp;

</div>

<p align="center">
  <img src="assets/visualization.png" width="720">
</p>

This repository includes the official pytorch implementation of Set AutoRregressive Modeling (SAR), presented in our paper:

**[Customize Your Visual Autoregressive Recipe with Set Autoregressive Modeling](https://arxiv.org/abs/)**

[Wenze Liu](https://poppuppy.github.io/), [Le Zhuo](https://le-zhuo.com/), [Yi Xin](https://synbol.github.io/), [Sheng Xia](https://github.com/travis-xia/), [Peng Gao](https://gaopengcuhk.github.io/), [Xiangyu Yue](https://xyue.io/)

MMLab, CUHK & Shanghai AI Lab & Nanjing University

Currently we are working to organize the code.

## Update

- [2024.10.15] [arXiv](https://arxiv.org/abs/2410.10511) preprint is available.

## Introduction

Welcome to **Set AutoRegressive Modeling (SAR)**! SAR extends causal learning from next-token prediction to the next-set setting. We show that AR and MAR are unified under the SAR paradigm with special choices of *sequence order* and *output intervals*. Further, a seamless pathway between AR and MAR is built by manipulating the order and intervals, where models trained in the transition states enjoy both merits of AR and MAR, such as few-step inference, KV cache acceleration, image editing, etc. 

## Features

- **Generalized AR Paradigm**: SAR conceptually unifies existing AR approaches, and provides broader design space to customize the training/inference process.
- **Fully Masked Transformer**: A new transformer architecture suitable for SAR.
- **Transition States**: The transition states in SAR offer new AR variants, which integrate both advantages of AR and MAR.

## Getting Started

### Prerequisites

We run the code on:

- Python 3.11
- PyTorch 2.3.1

## Acknowledgements

The code is built upon [LlamaGen](https://github.com/FoundationVision/LlamaGen), [MAR](https://github.com/LTH14/mar), [VAR](https://github.com/FoundationVision/VAR) and [MAE](https://github.com/facebookresearch/mae) (PyTorch). Thank for their great work.

## Citation

```bibtex
@article{liu2024customize,
  title={Customize Your Visual Autoregressive Recipe with Set Autoregressive Modeling},
  author={Liu, Wenze and Zhuo, Le and Xin, Yi and Xia, Sheng and Gao, Peng and Yue, Xiangyu},
  journal={arXiv preprint arXiv:2410.10511},
  year={2024}
}
```
