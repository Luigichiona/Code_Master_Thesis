# MSc Thesis Code – Intrusion Detection in IoMT (Internet of Medical Things)

This repository contains the code developed for the Master's thesis titled:

**"Comparative Analysis of Machine Learning Models for Intrusion Detection in Internet of Medical Things Environments"**  
Tilburg University – MSc Data Science & Society – 2025  
Author: Luigi Tomassini

## 📄 Contents

- `Master Thesis Code.ipynb`: Jupyter notebook implementing the full experimental pipeline, including:
  - Data preprocessing and exploration
  - Handling class imbalance with SMOTE
  - Training multiple models (XGBoost, LightGBM, CatBoost, TensorFlow, etc.)
  - Evaluation using various metrics and statistical comparisons

- `requirements.txt`: List of Python libraries required to run the code.

## ⚙️ Environment

Tested on Python 3.10 with the following key packages:
- numpy
- pandas
- matplotlib
- scipy
- scikit-learn
- imbalanced-learn (imblearn)
- xgboost
- tensorflow

## ▶️ How to Run

1. Install the required packages:
```bash
pip install -r requirements.txt
```

2. Open `Master Thesis Code.ipynb` in Jupyter or Google Colab.

## 📚 Dataset

This project uses the CICIoMT2024 dataset provided by the [Canadian Institute for Cybersecurity](https://www.unb.ca/cic/datasets/iomt.html), under a CC BY 4.0 license.

## 📘 Thesis Information

This code supports the thesis submitted to Tilburg University for the MSc in Data Science and Society program, under the supervision of the Department of Cognitive Science and Artificial Intelligence.
