# 🧠 Customer Segmentation with RFM & K-Means

This project analyzes e-commerce customer behavior using RFM (Recency, Frequency, Monetary) metrics and applies *K-Means Clustering* to segment customers into meaningful groups for business insights.

---

## 📂 Dataset

The dataset is a publicly available online retail transactional dataset containing purchases made between 2010 and 2011 by customers from the UK.

📎 Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail)

---

## 🧰 Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn)
- Matplotlib & Seaborn
- Plotly (for interactive visualizations)
- Jupyter Notebook

---

## 🔍 Project Phases

1. *Data Cleaning*
   - Removed missing values (e.g., null CustomerID, Description)
   - Removed outliers (e.g., negative Quantity and UnitPrice)
   - Filtered for UK transactions

2. *Feature Engineering*
   - Added TotalPrice = Quantity × UnitPrice
   - Extracted date-related features (Hour, Day, Month, Weekday, etc.)

3. *Exploratory Data Analysis*
   - Sales trend analysis (daily, hourly, monthly)
   - Top-selling items and customer purchase behavior

4. *RFM Analysis*
   - Defined RFM features per customer
   - Calculated RFM scores and normalized the values

5. *Customer Segmentation*
   - Applied KMeans clustering
   - Determined optimal number of clusters (Elbow method, Silhouette Score)
   - Assigned cluster labels to each customer

6. *Cluster Analysis*
   - Analyzed and interpreted each segment:
     - VIPs
     - Regular customers
     - Inactive customers

---

## 📊 Sample Insights

| Cluster | Recency ↓ | Frequency ↑ | Monetary ↑ | Customers |
|--------:|----------:|------------:|------------:|----------:|
| *0*   | 244       | 1.59        | 487         | 992       |
| *1*   | 40        | 4.71        | 1,783       | 2,905     |
| *2*   | 19        | 59.91       | 71,494      | 23        |

---

## 📈 Visualizations

- 📅 Sales trend by date, month, and weekday
- 🕒 Hourly purchasing behavior
- 🎯 RFM-based customer segmentation plots
- 📦 Top products by sales and quantity

![Daily Sales trend](https://github.com/user-attachments/assets/d881b194-ee38-43f6-9252-77a00b5a95c4)



## 🎯 Business Value

This segmentation enables targeted marketing:
- *Cluster 2 (VIPs):* Loyalty rewards & exclusive offers
- *Cluster 1:* Promotional campaigns to increase engagement
- *Cluster 0:* Win-back strategies for churned users

---

## 🚀 Future Work

- Apply advanced clustering algorithms (e.g., DBSCAN, Hierarchical)
- Predict customer lifetime value (CLV)
- Build a recommendation system based on user segments

---

## 📧 Contact

For collaboration or freelance projects:
*[Rahmani Mahdiye]*  
📧 [mahdiye.rahmani.ch@gmail.com]  
🔗 [www.linkedin.com/in/mahdiye-rahmani-998553110] 
🌍 [Portfolio or Website if any]
