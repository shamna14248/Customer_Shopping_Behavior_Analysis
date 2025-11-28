# 🛍️ Customer Shopping Behavior Analysis  
![Python](https://img.shields.io/badge/Python-3.10-blue)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-336791)
![PowerBI](https://img.shields.io/badge/Visualization-PowerBI-F2C811)


## 📌 Overview  
This project analyzes **3,900 customer purchase transactions** to uncover patterns in spending, product preferences, discounts, subscription behavior, and customer loyalty.  
The workflow integrates **Python + SQL + Power BI** to generate actionable business insights.

---

## 📊 Dataset Summary
- **Rows:** 3,900  
- **Columns:** 18  
- **Missing Values:** 37 (in Review Rating)  
- **Contains:**  
  - Demographics  
  - Product & purchase details  
  - Discounts & promotions  
  - Ratings & shipping types  

---

## 🧪 Exploratory Data Analysis (Python)
Key steps:
- Data loading, cleaning, and column standardization  
- Imputed missing values using **median rating per category**  
- Feature engineering:  
  - `age_group`  
  - `purchase_frequency_days`  
- Removed redundant fields  
- Loaded cleaned data into **PostgreSQL**  

---

## 🗄️ SQL Business Analysis  
Insights derived through SQL queries:

1. Revenue by gender  
2. High-spending customers using discounts  
3. Top 5 products by average review rating  
4. Standard vs. express shipping comparison  
5. Subscribers vs. non-subscribers revenue  
6. Products most dependent on discounts  
7. Customer segmentation: New, Returning, Loyal  
8. Top 3 products per category  
9. Repeat buyers & subscription link  
10. Revenue contribution by age groups  

---

## 📈 Power BI Dashboard  
A fully interactive dashboard includes:  
- Revenue heatmaps  
- Category-level insights  
- Customer segmentation visuals  
- Shipping and discount behavior  
- Top-rated & best-selling products  

---

## 💡 Business Recommendations
- Promote **subscriptions** with exclusive benefits  
- Introduce **loyalty rewards** for repeat customers  
- Optimize discount strategies  
- Focus marketing on **high-performing age groups**  
- Highlight **best-selling & top-rated products**  

---

├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── Customer_Shopping_Behavior_Analysis.sql
│
├── dashboard/
│   └── Customer_Shopping_Behavior_Analysis_Report.pbix
│
└── README.md



## 🛠️ Technologies Used
- Python (Pandas, NumPy, Matplotlib)  
- PostgreSQL  
- Power BI  
- Jupyter Notebook  

---

 

