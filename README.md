# 🛍 E-commerce Return Rate Reduction Analysis

This project analyzes product return behavior in an e-commerce business. It identifies high-return categories and customers, predicts return probability using a logistic regression model, and presents insights through an interactive Power BI dashboard.

---

## 🎯 Objective

- Understand key drivers behind product returns
- Predict which orders are likely to be returned
- Recommend strategies to reduce return rates

---

## 🛠 Tools & Technologies Used

- *Python*: Data cleaning, EDA, machine learning (pandas, seaborn, scikit-learn)
- *Power BI*: Dashboard creation and visual storytelling

---

## 🧪 Steps Performed

### 1. Data Cleaning & Feature Engineering (Python)
- Merged order and return datasets
- Created features like:
  - Delivery time
  - Return history of customer
  - Product rating, category
- Labeled data as returned or not

### 2. Exploratory Data Analysis (Python)
- Return rates by product category and region
- Impact of delivery time on return likelihood
- Visualization of return spikes during sales events

### 3. Model Building (Python)
- Logistic Regression to predict return probability
- Evaluated using accuracy, precision, and recall
- Output used to flag high-risk products

### 4. Dashboard Creation (Power BI)
- KPIs: Return rate, total returns, flagged items
- Charts:
  - Return rate by category
  - Return rate over time
  - Heatmap by customer region
  - Table of high-risk products with scores
- Interactive filters: Category, Region, Rating
