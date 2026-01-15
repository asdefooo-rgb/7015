# 7015
7015Final
# Medical Visual Question Answering (Med-VQA) with BLIP

This repository contains the implementation for the final project of **WOA7015 Advanced Machine Learning**.

## 📌 Project Overview
We explore the application of **Vision-Language Models (VLMs)** in medical imaging. Specifically, we compare a fine-tuned **BLIP** model against a traditional **CNN-LSTM** baseline on the **VQA-RAD** dataset.

## 🚀 Key Features
- **Patient-level Split:** Implemented MD5-based hashing to prevent data leakage between train/test sets.
- **Model Architecture:** - Baseline: ResNet18 + LSTM
  - Proposed: BLIP (Bootstrapping Language-Image Pre-training)
- **Performance:** Achieved **9.32%** accuracy on open-ended questions (vs 1.72% baseline) and solved the mode collapse issue.

## 📊 Results Snapshot
![Confusion Matrix](path_to_your_image_d57c0a.png)
*Figure: BLIP demonstrates superior semantic understanding compared to baseline.*

## 🛠️ How to Run
The entire pipeline is contained in `Final_Project_Notebook.ipynb`.
1. Open the notebook in **Google Colab**.
2. Mount your Google Drive.
3. Run the cells sequentially to reproduce the Data ETL, Training, and Evaluation steps.

## 👥 Authors
Group HaJeeMe (2022/2023 Sem 1)
