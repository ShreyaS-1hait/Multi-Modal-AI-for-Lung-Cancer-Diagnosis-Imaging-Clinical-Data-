# Multi-Modal AI for Lung Cancer Diagnosis
> Combining CT Scan Imaging + Clinical Data using Deep Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ShreyaS-1hait/Multi-Modal-AI-for-Lung-Cancer-Diagnosis-Imaging-Clinical-Data-/blob/main/AI_Multimodel_Lung_Cancer_Diagonsis.ipynb)

---

## Overview
A multi-modal AI system that diagnoses lung cancer by combining:
- **CT Scan Image Analysis** — ResNet50 deep learning model
- **Clinical Data Analysis** — Gradient Boosting Classifier
- **Fusion** — Equal weighted (50/50) combination of both models

## Results
| Model | Accuracy |
|-------|----------|
| Image Model (ResNet50) | 92.23% |
| Clinical Model (Gradient Boosting) | 84.96% |
| Dataset Size | 3,609 CT Scan Images |
| Classes | Malignant, Benign, Normal |

## Tech Stack
- Python, TensorFlow, Keras
- ResNet50 (Transfer Learning)
- Scikit-learn (Gradient Boosting)
- Streamlit (Web App)
- Google Colab + Google Drive

## How to Run
1. Open the notebook in Google Colab (badge above)
2. Mount your Google Drive
3 Dataset:
The dataset used is the **IQ-OTH/NCCD Lung Cancer Dataset** from Kaggle.
- The folder should contain:
  - `Malignant cases/`
  - `Benign cases/`
  - `Normal cases/`
  - `lungcancerdataset.csv`
- Download from: [Kaggle Dataset Link](https://www.kaggle.com/)
- After downloading, upload to your Google Drive at: https://drive.google.com/drive/folders/1GJN0Q6Qh42DRLo78TAHo2jDuinyGeBAv?usp=drive_link
4. Run all cells in order

## Author
Shreya R — GITAM University
