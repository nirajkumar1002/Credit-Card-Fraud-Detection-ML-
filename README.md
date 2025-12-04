# 🛡️ Credit Card Fraud Detection — Machine Learning Project

## ⭐ Overview
This repository contains an end-to-end Machine Learning project for **credit card fraud detection**, built using the popular Kaggle dataset. The problem is challenging due to **extreme class imbalance** (~0.17% fraud cases).  
This project demonstrates techniques for handling imbalanced data, training multiple models, optimizing thresholds, and evaluating the system for real-world deployment.

---

## 📊 Project Highlights

### ✔ Complete ML Pipeline
- Exploratory Data Analysis (EDA)
- Data preprocessing & scaling
- Stratified train-test split
- Handling class imbalance using:
  - Class weights  
  - Random oversampling  
- Multiple model training:
  - Logistic Regression
  - Random Forest
  - Random Forest + Oversampling
- Threshold tuning for business-specific optimization
- Feature importance analysis
- Model comparison table

### ✔ Best Model Achieved
**Random Forest + Oversampling + Threshold (0.40)**  
- **Precision:** 93.02%  
- **Recall:** 81.63%  
- **F1-score:** 0.8696  
- **ROC-AUC:** 0.9667  
- Extremely low false positives (only 6)

---



## 🧠 Dataset

This project uses the **Credit Card Fraud Detection** dataset from Kaggle:  
https://www.kaggle.com/mlg-ulb/creditcardfraud

Features:
- `V1`–`V28`: PCA components  
- `Time` and `Amount`  
- `Class`:  
  - 0 → Legitimate  
  - 1 → Fraud  

---

## 🚀 Running the Project

### Option 1 — Run the Notebook (Recommended)
Open the `notebooks/fraud_detection.ipynb` in Jupyter, Kaggle, or VSCode and execute step by step.

## Result Summary
| Model                                | Precision | Recall   | F1-score   | ROC-AUC |
| ------------------------------------ | --------- | -------- | ---------- | ------- |
| Logistic Regression                  | 0.06      | **0.92** | 0.11       | 0.9721  |
| Random Forest                        | **0.96**  | 0.75     | 0.8457     | 0.9572  |
| RF + Oversampling                    | 0.95      | 0.78     | 0.8539     | 0.9667  |
| RF + Oversampling + Threshold (0.40) | 0.93      | 0.82     | **0.8696** | 0.9667  |


### 🧩 Techniques Demonstrated

Handling imbalanced data

Feature scaling

Ensemble modeling

Oversampling

Custom threshold tuning

ROC/PR curves

Model interpretability

Reproducible ML workflows

### 🏁 Conclusion

This project shows how to design, build, and optimize a fraud detection system appropriate for real-world use. Through oversampling and threshold tuning, the final model achieves a strong balance between detecting fraud and minimizing customer inconvenience.

### 📬 Contact

Feel free to connect if you have questions or want help understanding any part of the project:

Niraj Kumar
Email: yesiamniraj@gmail.com
GitHub: github.com/nirajkumar1002

