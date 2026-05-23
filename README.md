# [# [你的论文完整英文标题]

This repository contains the official implementation for the paper: **"[你的论文标题]"**.

## 💡 Introduction

In this work, we explore inference-time scaling and uncertainty quantification for Large Language Models (LLMs). We propose **UCO-WRF** (Useq-MAP + Weighted Reward-Frequency voting), a novel approach designed to optimize the trade-off between model accuracy and inference compute costs. 

Compared to existing baselines like standard Best-of-N (BoN), Self-Consistency, and OptScale, our method achieves a superior Pareto frontier on challenging mathematical reasoning benchmarks.

## 📊 Main Results

*Here you can insert your main results table or a Pareto frontier plot (e.g., Accuracy vs. Token Efficiency).*

![Pareto Frontier Plot](assets/pareto_frontier.png)

*(Add a brief description of the table/plot above, e.g., "Performance comparison on MATH-500 and AIME 2024. UCO-WRF achieves higher accuracy with significantly fewer generated tokens.")*

## 🚀 Quick Start

### 1. Requirements & Installation

We recommend using Anaconda to manage your environment. The code has been tested on an **NVIDIA A100 (80GB)** GPU with PyTorch.

```bash
conda create -n uco-wrf python=3.10
conda activate uco-wrf

# Install PyTorch (adjust the CUDA version according to your environment)
pip install torch torchvision torchaudio --index-url [https://download.pytorch.org/whl/cu118](https://download.pytorch.org/whl/cu118)

# Install other dependencies
pip install -r requirements.txt]

[![Paper](https://img.shields.io/badge/Arxiv-2400.00000-B31B1B.svg)](https://arxiv.org/abs/...)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/release/python-390/)

This repository contains the official implementation for the paper: **"[你的论文标题]"**.

## 💡 Introduction

In this work, we explore inference-time scaling and uncertainty quantification for Large Language Models (LLMs). We propose **UCO-WRF** (Useq-MAP + Weighted Reward-Frequency voting), a novel approach designed to optimize the trade-off between model accuracy and inference compute costs. 

Compared to existing baselines like standard Best-of-N (BoN), Self-Consistency, and OptScale, our method achieves a superior Pareto frontier on challenging mathematical reasoning benchmarks.

## 📊 Main Results

*Here you can insert your main results table or a Pareto frontier plot (e.g., Accuracy vs. Token Efficiency).*

![Pareto Frontier Plot](assets/pareto_frontier.png)

*(Add a brief description of the table/plot above, e.g., "Performance comparison on MATH-500 and AIME 2024. UCO-WRF achieves higher accuracy with significantly fewer generated tokens.")*

## 🚀 Quick Start

### 1. Requirements & Installation

We recommend using Anaconda to manage your environment. The code has been tested on an **NVIDIA A100 (80GB)** GPU with PyTorch.

```bash
conda create -n uco-wrf python=3.10
conda activate uco-wrf

# Install PyTorch (adjust the CUDA version according to your environment)
pip install torch torchvision torchaudio --index-url [https://download.pytorch.org/whl/cu118](https://download.pytorch.org/whl/cu118)

# Install other dependencies
pip install -r requirements.txt
