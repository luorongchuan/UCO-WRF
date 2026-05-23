# [UCO-WRF:Uncertainty-Calibrated Dynamic OptScale and Weighted Reward Frequency Aggregation]

This repository contains the official implementation for the paper: **"[UCO-WRF:Uncertainty-Calibrated Dynamic OptScale and Weighted Reward Frequency Aggregation]"**.

## 💡 Introduction

In this work, we explore inference-time scaling and uncertainty quantification for Large Language Models (LLMs). We propose **UCO-WRF**, a novel approach designed to optimize the trade-off between model accuracy and inference compute costs. 

Compared to existing baselines like standard Best-of-N (BoN), Self-Consistency, and OptScale, our method achieves a superior Pareto frontier on challenging mathematical reasoning benchmarks.

## 🚀 Quick Start

### Step 1: Clone this repository and install dependencies

```bash
# Install dependencies
pip install -r requirements.txt
```

### Step 2: Download and place the data files

You can download the required datasets and model completions from Baidu Netdisk:
- [Baidu Netdisk ]([https://pan.baidu.com/s/1t5U6E5MAt3Rwj4DnjuzG2g?pwd=1234](https://pan.baidu.com/s/1G-9GD1EALkosiVBDeg-ruA)) (Extraction code: `[1234]`)

After downloading, please extract the files to the repository root.

### Step 3: Repository Structure

```text
.
├── MRT-r1_distill_llama8b/      # MR-Thinking baseline implementations (Llama-8B)
├── MRT-r1_distill_qwen7b/       # MR-Thinking baseline implementations (Qwen-7B)
├── SC-r1_distill_llama8b/       # Self-Consistency baselines (Llama-8B)
├── SC-r1_distill_qwen7b/        # Self-Consistency baselines (Qwen-7B)
├── WRF-Llama-8B/                # UCO-WRF method implementation (Standard Llama-8B)
├── WRF-r1_distill_llama8b/      # UCO-WRF method implementation (Llama-8B)
├── WRF-r1_distill_qwen7b/       # UCO-WRF method implementation (Qwen-7B)
├── train_predictor/             # Scripts and data for training the predictor
├── README.md                    # This document
└── requirements.txt             # Project dependencies












