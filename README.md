# indian-currency-classifier (CurrenSee)

## 🇮🇳 Indian Currency Classification using Deep Learning

## 📌 Overview
This project classifies Indian currency notes (₹10, ₹20, ₹50, ₹100, ₹200, ₹500, ₹2000) using CNN and Transfer Learning.

## 🚀 Models Developed
- V1: Baseline CNN
- V2: EfficientNetB0 (Feature Extraction)
- V3: Partial Fine-Tuning (Best Model)
- V4: Full Fine-Tuning

## 📊 Results

| Version | Accuracy | Validation Accuracy |
|--------|---------|---------------------|
| V1 | 97.62% | 88.89% |
| V2 | 96.41% | 93.02% |
| V3 | 97.86% | **94.60%** |
| V4 | 96.40% | 91.43% |

## 🏆 Final Model
Version 3 selected due to best generalization.

## 🖼 Sample Predictions
(Add images here)

## ⚙️ Tech Stack
- TensorFlow / Keras
- Python
- OpenCV
- Matplotlib

## 📂 Dataset
[Kaggle Dataset Link]

## ▶️ How to Run
```bash
pip install -r requirements.txt
python src/predict.py
