# Customer Segmentation using RFM & Clustering 📊🧠

This project focuses on customer segmentation for a UK-based Online Retail dataset. The goal is to understand customer purchase behaviour and categorize customers into meaningful groups using **RFM analysis** (Recency, Frequency, Monetary) and **clustering algorithms**.

---

## 🚀 Project Workflow

### 1) 🧹 Data Cleaning & Preprocessing
- Removed null values, negative quantity records (cancellations/returns)
- Converted invoice date into proper time format
- Handled duplicates and formatted dataset for analysis

### 2) 🔍 Exploratory Data Analysis (EDA)
- Visualized patterns like top selling countries, order distribution, revenue trends
- Identified purchasing behaviour patterns across customers

### 3) 🧾 RFM Analysis
- Calculated Recency, Frequency, Monetary value for each customer
- Normalized & scored RFM values
- Created customer segments based on RFM scoring

### 4) 🤖 Clustering
- Algorithms used:
  - K-Means
  - Gaussian Mixture Model (GMM)
  - DBSCAN
- Evaluated clusters using silhouette score

### 5) 🏁 Final Output
- 💎 High Value Customers
- ⭐ Potential Loyal Customers
- ⚠️ At Risk Customers
- 🧊 Low Value Customers

---

## 🧰 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Plotly
- Scikit-Learn

---

## 🎯 Key Objective
Segment customers based on purchase behaviour to design personalized marketing strategies and improve retention.
