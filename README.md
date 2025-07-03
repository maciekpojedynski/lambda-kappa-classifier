# Lambda vs Kappa Architecture Classifier

This project contains a Python implementation of a classification model that predicts whether a given data processing scenario is best suited to a **Lambda** or **Kappa** architecture.

## ✨ Overview

The model:
- Uses a **Decision Tree Classifier** to distinguish between Lambda and Kappa architectures.
- Applies feature engineering to create additional indicators (e.g., high TTL, request frequency, cloud usage).
- Encodes categorical variables via **One-Hot Encoding**.
- Outputs accuracy and a detailed classification report.

## 🗃️ Files

- `train_decision_tree.py` – main script for training and evaluating the model
- `data/` – directory with sample CSV files containing training data
- `README.md` – this documentation
- `.gitignore` – excludes unnecessary files from Git

## 🚀 Quick Start

1. Install dependencies:
   ```bash
   pip install pandas scikit-learn numpy
