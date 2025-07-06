# customer-segmentation
# 🛍️ Customer Segmentation using K-Means Clustering

This project is part of my internship task at **Prodigy Infotech**. The objective is to use **K-Means Clustering** to segment customers of a mall based on their **Annual Income** and **Spending Score** using unsupervised machine learning.

---

## 📌 Problem Statement

We aim to group mall customers into distinct segments based on their purchasing behavior. This helps the business understand customer patterns and improve marketing strategies.

---

## 📊 Dataset

- **Source:** [Kaggle Dataset - Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **File Used:** `Mall_Customers.csv`
- **Features:**
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

---

## 🧠 What is K-Means Clustering?

K-Means is an **unsupervised machine learning algorithm** that divides data into **K distinct clusters** based on feature similarity. It works by:
1. Picking K centroids
2. Assigning data points to the nearest centroid
3. Recalculating centroids
4. Repeating until convergence

---

## 🔍 Steps Followed

1. **Imported libraries** like Pandas, Matplotlib, Seaborn, Scikit-learn
2. **Loaded** and **explored** the dataset
3. Selected key features: `Annual Income`, `Spending Score`
4. **Scaled features** using `StandardScaler` to normalize values
5. **Used Elbow Method** to find optimal number of clusters (k=5)
6. Applied **KMeans algorithm**
7. **Visualized clusters** using scatter plot
8. Analyzed cluster statistics

---

## 📈 Output: Cluster Analysis

| Cluster | Age (avg) | Income (k$) | Spending Score | Customer Type |
|--------:|-----------|-------------|----------------|-----------------------------|
| 0 | 42.7 | 55.3 | 49.5 | Balanced, average income/spending |
| 1 | 32.7 | 86.5 | 82.1 | High income & high spenders |
| 2 | 25.3 | 25.7 | 79.4 | Young with low income but spend a lot |
| 3 | 41.1 | 88.2 | 17.1 | Rich but low spenders |
| 4 | 45.2 | 26.3 | 20.9 | Low income & low spending |

---

## 📸 Visualizations

- Elbow Curve (to choose number of clusters)
- Cluster Plot (Income vs Spending Score)

---

## 🚀 Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## ✨ Author

**Gokul S** 

---

## 📁 Files in this Project

- `Mall_Customers.csv` – Dataset file  
- `customer_segmentation.ipynb` – Source code  
- `README.md` – Project documentation  

---

## 📬 Feel free to connect with me!

