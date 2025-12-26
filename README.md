# 🤖 LLM & Deep Learning Projects

This repository contains hands-on projects focused on **fine-tuning and evaluating transformer-based language models**. The primary goal is to demonstrate practical skills in adapting pretrained LLMs to downstream tasks using modern deep learning frameworks.

Projects in this repository emphasize:
- 🧠 Supervised fine-tuning of pretrained language models  
- 🧩 Task-specific data preparation and tokenization  
- ⚙️ Training configuration and optimization  
- 📊 Quantitative evaluation of model performance  

---

## 📓 Notebooks

### 🎭 Emotion Dataset Fine-Tuning

In this notebook, I fine-tune a transformer-based model to classify text into one of six emotion categories using the Emotion dataset. The objective is to move beyond zero-shot inference and train a model that is explicitly adapted to the structure and label distribution of the dataset.

A pretrained **DistilBERT** model is fine-tuned on labeled examples, enabling the classifier to learn task-specific linguistic patterns that improve predictive accuracy relative to prompt-based or zero-shot approaches.

The notebook covers the full fine-tuning workflow, including:
- 📥 Dataset loading and inspection  
- ✂️ Text preprocessing and tokenization  
- 🏗️ Model initialization from pretrained weights  
- 🔁 Supervised training using cross-entropy loss  
- 📈 Evaluation using standard classification metrics

## Skills 

![](https://img.shields.io/badge/PyTorch-informational?style=flat&logo=pytorch&logoColor=white&color=003865) ![](https://img.shields.io/badge/HuggingFace-informational?style=flat&logo=huggingface&logoColor=white&color=003865) ![](https://img.shields.io/badge/Colab-informational?style=flat&logo=Colab&logoColor=white&color=003865)
