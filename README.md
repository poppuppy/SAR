# 🚀 Customize Your Visual Autoregressive Recipe with Set Autoregressive Modeling
<div align="center">

[arXiv](https://arxiv.org/abs/)&nbsp;
[project page](https://poppuppy.github.io/sar.github.io/)&nbsp;

</div>
![Project Logo](link-to-your-logo.png)

This repository includes the official pytorch implementation of Set AutoRregressive Modeling (SAR), presented in our paper:

**[Customize Your Visual Autoregressive Recipe with Set Autoregressive Modeling](https://arxiv.org/abs/)**

Wenze Liu, Le Zhuo, Yi Xin, Sheng Xia, Peng Gao, Xiangyu Yue

MMLab, CUHK & Shanghai AI Lab & Nanjing University

Currently we are working to organize the code.

## 🍀 Update

- [2024.10.15] [arXiv](https://arxiv.org/abs/) preprint is available.

## 🔥 Introduction

Welcome to **Set AutoRegressive Modeling (SAR)**! SAR extends causal learning from next-token prediction to the next-set setting. We show that AR and MAR are unified under the SAR paradigm with special choices of *sequence order* and *output intervals*. Further, a seamless pathway between AR and MAR is built by manipulating the order and intervals, where models trained in the transition states enjoy both merits of AR and MAR, such as few-step inference, KV cache acceleration, image editing, etc. 

## 📦 Features

- **Generalized AR Paradigm**: SAR conceptually unifies existing AR approaches, and provides broader design space to customize the training/inference process.
- **Fully Masked Transformer**: A new transformer architecture suitable for SAR.
- **Transition States**: The transition states in SAR offers new AR variants, which integrate both advantages of AR and MAR.

## ⚡ Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.8+
- Necessary libraries (e.g., PyTorch, NumPy)

### Installation

To install **SAR**, follow these steps:

```bash
git clone https://github.com/yourusername/sar-project.git
cd sar-project
pip install -r requirements.txt
