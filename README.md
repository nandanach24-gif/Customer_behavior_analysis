
# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping data from 3,900 purchases.
The goal is to understand customer behavior, spending patterns, and product performance to support business decisions.

---

## 📊 Dataset Details
- Total Records: 3,900
- Total Columns: 18
- Missing Values: 37 (Review Rating column)

The dataset includes:
- Customer details (Age, Gender, Location, Subscription Status)
- Purchase details (Item, Category, Purchase Amount, Season, Size, Color)
- Shopping behavior (Discount Applied, Previous Purchases, Frequency, Rating, Shipping Type)

---

## 🐍 Data Cleaning & Preparation (Python)
- Loaded dataset using Pandas
- Checked structure using `df.info()` and `describe()`
- Handled missing values using median imputation
- Renamed columns to snake_case format
- Created new features (age_group, purchase frequency)
- Removed redundant columns
- Loaded cleaned data into PostgreSQL

---

## 🗄️ SQL Analysis
Performed business analysis to answer:

- Revenue by gender
- High-spending discount users
- Top 5 products by rating
- Subscribers vs non-subscribers revenue comparison
- Revenue by age group
- Customer segmentation (New, Returning, Loyal)

---

## 📈 Power BI Dashboard
Built an interactive dashboard to visualize:
- Revenue trends
- Customer segments
- Product performance
- Subscription insights

---

## 💡 Key Insights
- Subscribers generate higher average revenue
- Loyal customers contribute consistent sales
- Some products depend heavily on discounts
- Certain age groups drive more revenue

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy)
- PostgreSQL
- Power BI
