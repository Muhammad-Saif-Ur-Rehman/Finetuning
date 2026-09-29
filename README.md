# 🚀 Finetuning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

This repository contains code, scripts, and Jupyter Notebooks related to fine-tuning machine learning models and Large Language Models (LLMs). It serves as a central hub for experimenting with custom datasets, parameter-efficient fine-tuning (PEFT) techniques, and model evaluation.

## 🌟 Key Features

* **LLM Fine-Tuning**: Scripts for fine-tuning open-source models (e.g., Gemma) on custom instructional datasets.
* **Parameter-Efficient Techniques**: Implementations of **LoRA** (Low-Rank Adaptation) and **QLoRA** for efficient training on consumer-grade GPUs.
* **Inference Scripts**: Ready-to-use scripts to test and evaluate the fine-tuned checkpoints.

## 🛠️ Tech Stack

* **Language**: Python
* **Frameworks**: PyTorch, TensorFlow
* **Libraries**: HuggingFace `transformers`, `peft`, `trl`, `datasets`, `bitsandbytes` (for quantization)
* **Environment**: Jupyter Notebooks / Python Scripts

## 📂 Repository Structure

```text             # Jupyter notebooks for interactive training and EDA
├── Task 1 Gemma finetuning for classification on SQL Query based dataset/
│   ├── finetuning-gemma-for-sql-ingestion-classification.ipynb
├── Task 2 Gemma finetuning for classification based on datapackets/
│   ├── finetuning-gemma-for-classification-on-dpkts.ipynb
└── README.md              # Project documentation
