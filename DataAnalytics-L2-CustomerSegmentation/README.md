# 🛍️ Customer Segmentation using RFM Analysis & K-Means

## 📌 Project Overview

This project focuses on customer segmentation using the **Online Retail Dataset**. The objective is to analyze customer purchasing behavior and divide customers into meaningful groups using **RFM Analysis** and **K-Means Clustering**.

This project was completed as part of the **Data Analytics Internship at Oasis Infobyte**.

---

## 🎯 Objectives

- Analyze customer purchasing behavior
- Perform RFM (Recency, Frequency, Monetary) analysis
- Identify valuable and inactive customers
- Apply K-Means clustering for customer segmentation
- Determine the optimal number of clusters
- Visualize customer segments
- Generate meaningful business insights

---

## 📂 Dataset

**Dataset:** UCI Online Retail Dataset

The dataset contains transactional information from an online retail store.

### Important Features

- `InvoiceNo` – Invoice number
- `StockCode` – Product code
- `Description` – Product description
- `Quantity` – Number of items purchased
- `InvoiceDate` – Date and time of transaction
- `UnitPrice` – Price per item
- `CustomerID` – Unique customer identifier
- `Country` – Customer's country

---

## 🛠️ Technologies & Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Methodology

### 1. Data Loading & Exploration

The Online Retail dataset was loaded using Pandas and its structure, dimensions, columns and sample records were analyzed.

### 2. Data Cleaning

The dataset was cleaned by:

- Handling missing Customer IDs
- Removing invalid transactions
- Handling cancelled invoices
- Removing records with non-positive quantities
- Removing records with invalid prices

### 3. RFM Analysis

Three important customer metrics were calculated:

**Recency:**  
Number of days since the customer's most recent purchase.

**Frequency:**  
Number of purchases made by the customer.

**Monetary:**  
Total amount spent by the customer.

### 4. Feature Scaling

RFM features were standardized before applying the clustering algorithm.

### 5. K-Means Clustering

K-Means clustering was applied to group customers based on their RFM characteristics.

Different values of K were tested using:

- Elbow Method
- Silhouette Score

### 6. Customer Segmentation

Customers were assigned to different clusters based on their purchasing behavior.

---

## 📊 Analysis & Visualization

The project includes visualizations such as:

- RFM distributions
- Elbow Method plot
- Silhouette Score plot
- Customer cluster visualization
- Cluster-wise customer analysis

---

## 💡 Key Insights

The clustering analysis helps identify different types of customers, such as:

- 🏆 High-value customers
- 💎 Loyal customers
- 🛒 Regular customers
- ⚠️ Customers requiring attention
- 💤 Inactive or low-value customers

These segments can help businesses create targeted marketing strategies and improve customer retention.

---

## 📁 Project Structure

```text
DataAnalytics-L2-CustomerSegmentation/
│
├── Customer_Segmentation_RFM_KMeans.ipynb
└── README.md

## 👨‍💻 Author

**Nishant Tyagi - Data Analytics Intern, Oasis Infobyte**
