# 🚀 Customize Your Visual Autoregressive Recipe with Set Autoregressive Modeling
<div align="center">

[![arXiv]](https://arxiv.org/abs/)&nbsp;
[![project page]](https://poppuppy.github.io/sar.github.io/)&nbsp;

</div>
![Project Logo](link-to-your-logo.png)

## 🔥 Introduction

Welcome to **Set AutoRegressive Modeling (SAR)**! SAR extends causal learning from next-token prediction to the next-set setting. We show that AR and MAR are unified under the SAR paradigm with special choices of *sequence order* and *output intervals*. Further, a seamless pathway is presented by manipulating the order and intervals, where models trained in the transition states enjoy both merits of AR and MAR, such as few-step inference, KV cache acceleration, image editing, etc. 

## 📦 Features

- **Generalized AR Framework**: Transition seamlessly from traditional AR to SAR, accommodating flexible sequence ordering.
- **Fully Masked Transformer**: Our straightforward architecture designed specifically for SAR.
- **Performance Insights**: Analyze the impact of sequence order and output intervals on model performance.
- **Photo-Realistic Image Synthesis**: Train a 900M text-to-image model capable of generating high-resolution images.

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
