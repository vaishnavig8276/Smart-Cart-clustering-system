# SmartCart Clustering System

## 📌 Project Overview
SmartCart is a growing e-commerce platform serving customers across multiple countries. Currently, the platform uses generic marketing and engagement strategies, leading to inefficient marketing spend, missed opportunities to retain high-value customers, and delayed identification of churn-prone users. 

This project builds an **intelligent customer segmentation system** using unsupervised machine learning. By analyzing historical customer transaction data, the system groups customers into meaningful clusters based on purchasing behavior, engagement levels, and loyalty indicators. These data-driven insights empower personalized marketing and improve customer retention.

## 📊 Dataset Description
The dataset contains historical customer transaction data with the following specifications:
* **Total Records:** 2,240 customers
* **Total Attributes:** 22 features
* **Key Feature Categories:** Demographics, Purchase Behavior, Website Activity, and Campaign Response.

## 🛠️ Tech Stack
* **Language:** Python
* **Environment:** Windows, VS Code, Jupyter
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn

## 🚀 Installation & Setup
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```powershell
   git clone [https://github.com/vaishnavig8276/Smart-Cart-clustering-system.git](https://github.com/vaishnavig8276/Smart-Cart-clustering-system.git)
   cd Smart-Cart-clustering-system
   ```

<div align="center">
  <h1>🛍️ SmartCart Clustering System</h1>
  <p><i>An Intelligent E-Commerce Customer Segmentation Engine</i></p>

  <!-- Tech Badges -->
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" alt="Status">
</div>

<br>

## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Business Value](#-business-value)
- [Tech Stack](#-tech-stack)
- [Workflow & Methodology](#-workflow--methodology)
- [Repository Structure](#-repository-structure)
- [Getting Started](#-getting-started)
- [Future Scope](#-future-scope)

## 🎯 Project Overview
SmartCart is a growing e-commerce platform serving customers across multiple countries[cite: 1]. Currently, the platform uses generic marketing and engagement strategies, leading to inefficient marketing spend, missed opportunities to retain high-value customers, and delayed identification of churn-prone users[cite: 1].

This project builds an **intelligent customer segmentation system** using unsupervised machine learning[cite: 1]. By analyzing historical customer transaction data, the system groups customers into meaningful clusters based on purchasing behavior, engagement levels, and loyalty indicators[cite: 1]. 

## 💡 Business Value
Once the model clusters the data, the business can take direct action:

| Customer Segment | Description | Marketing Strategy |
|------------------|-------------|--------------------|
| 👑 **VIP / High-Value** | Frequent buyers with high average order value. | VIP rewards, early access to new product drops. |
| ⚠️ **Churn-Prone** | Previously active, currently dormant. | Win-back campaigns, targeted push notifications. |
| 🛍️ **Bargain Hunters** | Purchase mainly during sales or clearance. | Highlight discount codes and bulk-buy offers. |

## 🛠️ Tech Stack
* **Language:** Python
* **Data Engineering:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (K-Means, PCA, DBSCAN)
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## ⚙️ Workflow & Methodology
1. **Data Ingestion:** Load historical customer transactions from `smartcart_customers.csv`[cite: 1].
2. **EDA & Preprocessing:** Handle missing values, apply feature scaling (StandardScaler), and identify outliers.
3. **Feature Engineering:** Build RFM (Recency, Frequency, Monetary) metrics to capture purchasing habits.
4. **Modeling:** Train unsupervised clustering algorithms.
5. **Optimization:** Determine the optimal number of clusters using the **Elbow Method** and **Silhouette Score**.

## 📂 Repository Structure
```text
Smart-Cart-clustering-system/
├── smartcart.ipynb             # Main notebook containing EDA, modeling, and evaluation[cite: 1]
├── smartcart_customers.csv     # Raw dataset containing transaction records[cite: 1]
└── README.md                   # Project documentation[cite: 1]
