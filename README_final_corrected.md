# 📊 Bank Marketing Campaign Analysis

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/bedrock510/bank-marketing-complete-fresh/blob/main/notebooks/bank_marketing_corrected_final.ipynb)

This project uses machine learning to predict whether a client will subscribe to a term deposit, based on data from a Portuguese bank's telemarketing campaigns.

## 📁 Project Structure

- `notebooks/bank_marketing_corrected_final.ipynb` – Final notebook (Colab-ready)
- `bank-additional-full.csv` – Dataset
- `README.md` – This file

## 🚀 How to Run

1. Click the **Open in Colab** badge above.
2. The notebook will launch in Google Colab.
3. All data loads automatically from GitHub.
4. Run each cell top to bottom.

## 📊 What’s Inside

- Exploratory Data Analysis (EDA)
- Visualization of categorical and numeric features
- Logistic Regression & Random Forest models
- Model evaluation using ROC AUC, confusion matrix, and classification report
- Business insights and next-step recommendations

## 🧠 Key Findings

- Target subscription rate is low (imbalanced dataset)
- Best predictors include: `month`, `contact`, `poutcome`, `education`
- Random Forest performed best among tested models

## 📌 Dataset Source

[UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
