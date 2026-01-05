# E-commerce Data Analysis (Python)

This project simulates the analysis of an online store dataset using Python.  
The goal is to extract **business insights** from transactional data, such as:

- Total revenue and Average Order Value (AOV)
- Revenue by product category
- Monthly revenue trends (seasonality)
- New vs returning customers

---

## 📦 Dataset

The dataset is artificially generated using Python and contains:

- **1000 orders**
- **~200 unique customers**
- **5 product categories:**  
  `Electronics`, `Fashion`, `Home Decor`, `Beauty`, `Accessories`

Main columns include:

- `order_date` – date of the order  
- `customer_id` – unique ID for each customer  
- `category` – product category  
- `order_value` – total order value  
- `quantity` – number of items in the order  

---

## 🎯 Business Questions

Some of the key questions explored in this analysis:

1. How much revenue did the e-commerce generate in the period?
2. What is the Average Order Value (AOV)?
3. Which product categories generate the most revenue?
4. How does revenue evolve month by month?
5. What is the proportion of **new vs returning customers**?

---

## 🛠 Tech Stack

- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Google Colab** – development environment

---

## 📊 Analysis Overview

The main steps in the notebook include:

1. **Data Generation & Loading**
   - Synthetic e-commerce dataset created using NumPy & Pandas.

2. **Exploratory Data Analysis (EDA)**
   - Dataset structure, descriptive statistics and initial exploration.

3. **Revenue Metrics**
   - Total revenue
   - Average Order Value (AOV)
   - Number of unique customers

4. **Revenue Over Time**
   - Monthly revenue analysis
   - Line chart visualizations

5. **Revenue by Category**
   - Total revenue per product category
   - Comparison using bar charts

6. **Customer Behavior**
   - Orders per customer
   - Classification into **New (1 order)** vs **Returning (2+ orders)**
   - Distribution analysis

---

## 🔍 Key Insights (Example)

> - Most revenue comes from returning customers, indicating strong retention.  
> - Average Order Value is relatively stable across categories.  
> - Fashion shows the highest AOV in this simulation, while Beauty shows lower order values on average.  
> - This suggests opportunities in **customer acquisition** and **category-focused strategies**.

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/ecommerce-data-analysis.git

2. Open the notebook:

In Jupyter Notebook, or

Upload ecommerce_analysis.ipynb to Google Colab

3. (Optional) Install dependencies:
pip install pandas numpy matplotlib

4. Run all cells from top to bottom.

Future Improvements

Add more realistic business rules to the dataset

Include profit margin and cost analysis

Perform cohort analysis for customer retention

Build an interactive dashboard (Power BI / Streamlit)

 About

This project is part of my data analytics learning journey and portfolio.
I am currently developing skills in:

Data analysis & storytelling

Python for data

Business-driven insights

Feel free to reach out or share feedback
