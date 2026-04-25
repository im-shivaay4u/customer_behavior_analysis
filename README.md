# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories.  
The goal is to extract meaningful insights related to **customer segments, spending habits, product preferences, and subscription behavior** to support business decision-making. :contentReference[oaicite:0]{index=0}

---

## 📊 Dataset Summary
- **Total Rows:** 3,900  
- **Total Columns:** 18  
- **Key Features:**
  - Customer Demographics: Age, Gender, Location, Subscription Status  
  - Purchase Details: Item, Category, Amount, Season, Size, Color  
  - Behavioral Data: Discounts, Promo Codes, Purchase Frequency, Ratings, Shipping Type  
- **Missing Values:** 37 values in *Review Rating* column :contentReference[oaicite:1]{index=1}  

---

## 🧹 Data Preprocessing (Python)
- Data cleaning using **pandas**
- Handled missing values using **median imputation**
- Renamed columns to **snake_case**
- Feature Engineering:
  - `age_group` creation
  - `purchase_frequency_days` mapping
- Removed redundant columns (promo_code_used)
- Loaded cleaned data into **PostgreSQL** database :contentReference[oaicite:2]{index=2}  

---

## 🧠 Data Analysis (SQL)
Performed business-driven analysis using SQL:

- Revenue comparison by gender  
- High-spending customers using discounts  
- Top 5 highest-rated products  
- Shipping type impact on spending  
- Subscriber vs Non-subscriber analysis  
- Discount-dependent products  
- Customer segmentation (New, Returning, Loyal)  
- Top products by category  
- Repeat buyers vs subscription behavior  
- Revenue contribution by age group :contentReference[oaicite:3]{index=3}  

---

## 📈 Dashboard (Power BI)
An interactive dashboard was built to visualize:
- Revenue trends
- Customer segmentation
- Sales by category
- Subscription insights
- Age-group based revenue  

(*Refer to dashboard image in project files*) :contentReference[oaicite:4]{index=4}  

---

## 🔍 Key Insights
- Loyal customers form the largest segment  
- Express shipping users tend to spend more  
- Discounts significantly influence product sales  
- Certain age groups contribute higher revenue  
- Subscription does not always guarantee higher spending  

---

## 💡 Business Recommendations
- Promote **subscription benefits**  
- Implement **customer loyalty programs**  
- Optimize **discount strategies**  
- Highlight **top-performing products**  
- Use **targeted marketing** based on customer segments :contentReference[oaicite:5]{index=5}  

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy)
- **SQL** (PostgreSQL)
- **Power BI**
- **Jupyter Notebook**

---

## 📂 Project Structure
