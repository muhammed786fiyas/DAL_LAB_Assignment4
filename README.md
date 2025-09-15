## 📌 **Author**

- Name: **MUHAMMED FIYAS**  
- Roll no.: **DA25M018**  
- *M.Tech DS&AI, IIT Madras*

---

# 📊 **DA5401 Assignment 4 – GMM-Based Synthetic Sampling for Imbalanced Data**

Welcome to the **DA5401** project on **class imbalance handling using Gaussian Mixture Models (GMM)**.  
In this notebook, we build upon baseline Logistic Regression and explore how **GMM-based resampling** can improve minority class detection in **fraudulent transaction classification**.

---

## 🎯 **Objective**

The goal of this assignment is to evaluate **GMM-driven oversampling techniques** (with and without Clustering-Based Undersampling) and compare them against a baseline model. Specifically, we analyze:

1. **Baseline Logistic Regression on imbalanced dataset**  
2. **GMM Oversampling (synthetic minority data generation)**  
3. **GMM + Clustering-Based Undersampling (hybrid approach)**  

---

## 📂 Project Structure
```
DAL_LAB_Assignment4/
├── Fraud_Detection_GMM.ipynb # Jupyter Notebook (analysis, models, visualizations)
└── README.md        # Project documentation

```

---

## 🛠️ **What’s Included**

| Section | Description |
|---------|-------------|
| **Data Analysis & Baseline** | Explored dataset, visualized class imbalance, trained Logistic Regression baseline. |
| **GMM Oversampling** | Implemented Gaussian Mixture Model to generate synthetic minority samples. |
| **Hybrid Method (GMM + CBU)** | Applied undersampling on majority class + GMM oversampling on minority for balanced data. |
| **Performance Comparison** | Evaluated Accuracy, Precision, Recall, F1-score across Baseline, GMM, and GMM+CBU. |
| **Conclusion** | Discussed trade-offs between recall and precision, recommended balanced approach. |

---

## 📊 **Visualizations Used**

-   **Pie Chart** – Original class imbalance.  
-   **Confusion Matrices** – For baseline and GMM-based models.  
-   **Bar Plots / Tables** – Comparison of performance metrics across models.  
-   **Cluster Visualization** – Minority data synthesis using GMM.  

---

## ✅ **Key Insights**

-   ⚠️ The dataset is highly **imbalanced**, making recall a challenge in baseline models.  
-   📉 **Baseline Logistic Regression** achieved high accuracy (99.9%) and strong precision (0.83), but recall was limited (0.64).  
-   🚀 **GMM Oversampling** drastically improved recall (0.90) but precision fell sharply (0.08), leading to very low F1-score (0.14).  
-   🔄 **GMM + CBU** balanced performance: recall remained high (0.89) with better precision (0.13), improving F1-score (0.23).  
-   🎯 **Trade-off:** Oversampling enhances fraud detection coverage but introduces false positives.  
-   ✅ **Recommendation:** Use **GMM + CBU hybrid method** for practical fraud detection, as it balances sensitivity (recall) and specificity (precision).  



