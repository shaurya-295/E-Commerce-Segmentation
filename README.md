# 🛍️ Customer Segmentation in E-commerce

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Platform](https://img.shields.io/badge/platform-Google%20Colab-yellow)

## 📌 Problem Statement

This project aims to segment customers based on their purchasing habits and browsing behavior. It also includes a supervised classification task to identify **High Spenders** using customer activity metrics.

---

## 🎯 Objectives

- Group similar customers using **unsupervised clustering**.
- Classify customers as **High** or **Low Spenders** using a **Random Forest Classifier**.
- Visualize the clusters using **PCA**.
- Evaluate classification performance using accuracy, precision, recall, and confusion matrix.

---

## 🚀 Technologies Used

- **Python** (3.8+)
- **Google Colab**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Visualization
- **Scikit-learn** – ML models, evaluation, preprocessing
- **Google Colab Files** – Dataset upload

---

## 🧠 Algorithms

| Task              | Algorithm                   | Type             |
|-------------------|------------------------------|------------------|
| Classification    | Random Forest Classifier     | Supervised       |
| Clustering        | K-Means Clustering           | Unsupervised     |
| Dimensionality Reduction | PCA (Principal Component Analysis) | Feature Reduction |

---

## 📊 Features

- 📁 Upload your own customer dataset (`.csv`)
- ⚙️ Automatic feature engineering (`TotalPrice`, aggregations)
- 🎯 Classification of spenders with performance metrics
- 🔍 Cluster customers into segments using K-Means
- 📈 Visual insights with PCA and Elbow Method

---

## 🖼️ Visualizations

- Confusion Matrix Heatmap  
- Elbow Plot for Optimal Clusters  
- PCA Scatter Plot of Customer Clusters  

> Screenshots included in the `output/` folder (or your report).

---

## 📁 Dataset

The dataset should include the following fields:  
`InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country`

> A sample dataset is provided in the repo. Replace with your own for experimentation.

---

## 🧪 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**

- **Confusion Matrix**

---

## 📝 How to Use

1. **Clone this repo**  
   ```bash
   git clone https://github.com/your-username/ecommerce-customer-segmentation.git
## RESULT 
![Screenshot 2025-04-18 153855](https://github.com/user-attachments/assets/0eebd5b5-8da9-4b25-b116-0957cae99065)
![Screenshot 2025-04-18 153916](https://github.com/user-attachments/assets/9000aa7e-4e09-4530-9161-f92adae885ee)
