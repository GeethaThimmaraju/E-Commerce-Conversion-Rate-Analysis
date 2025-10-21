# E-Commerce Conversion Rate Analysis

## Project Overview
This project analyzes an e-commerce dataset to understand customer behavior, identify factors influencing conversion, and provide actionable recommendations to improve the online store's conversion rate. The analysis includes data cleaning, exploratory data analysis (EDA), cohort analysis, conversion funnel estimation, and business insights.

---

## 🚀 Objective
- Analyze customer transactions to identify trends and patterns.
- Calculate conversion rates and understand purchase behavior.
- Generate actionable insights for marketing, product, and sales strategies.
- Visualize findings through charts and graphs for easy interpretation.

---

## 🗂 Dataset
- The dataset contains online retail transactions including:
  - `InvoiceNo`: Transaction ID
  - `StockCode`: Product code
  - `Description`: Product name
  - `Quantity`: Number of items purchased
  - `InvoiceDate`: Date and time of transaction
  - `UnitPrice`: Price per item
  - `CustomerID`: Unique customer identifier
  - `Country`: Customer location

**Source:** [Kaggle - Online Retail Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

---

## 🛠 Tools & Libraries
- **Python**: Data manipulation and analysis
- **Pandas** & **NumPy**: Data cleaning and preprocessing
- **Matplotlib** & **Seaborn**: Visualization
- **Jupyter Notebook / Google Colab**: Project environment

---

## 📊 Analysis Performed
1. **Data Cleaning & Preprocessing**
   - Handled missing values and removed canceled transactions
   - Converted date columns and created calculated fields like `TotalPrice`

2. **Exploratory Data Analysis (EDA)**
   - Top-selling products
   - Revenue by country
   - Sales by hour of day
   - Correlation between quantity, price, and revenue

3. **Conversion Analysis**
   - Estimated conversion rate using unique customers and orders
   - Cohort analysis to track repeat customer behavior

4. **Insights & Recommendations**
   - Peak sales hours and days
   - Product and country-specific trends
   - Suggestions to increase conversion rate and revenue

---

## 📈 Visualizations
### Top Selling Products
![Top Selling Products](visuals/top_products.png)

### Revenue by Country
![Revenue by Country](visuals/revenue_by_country.png)

### Sales by Hour of Day
![Sales by Hour](visuals/sales_by_hour.png)

### Correlation Heatmap
![Correlation Heatmap](visuals/correlation_heatmap.png)

### Cohort Analysis Table
![Cohort Analysis](visuals/cohort_analysis.png)

> Replace the above placeholders with your actual screenshots from Jupyter Notebook or Google Colab.

---

## 💡 Key Insights
- Peak sales occur during **[fill in peak hours]**  
- Top products include **[fill in top products]**  
- Countries with low sales may require targeted marketing or localization  
- Estimated conversion rate: **[fill in %]** — potential to improve with targeted campaigns  


