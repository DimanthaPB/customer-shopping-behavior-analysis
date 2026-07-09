# 🛍️ Customer Shopping Behavior Analysis

## 📖 Overview

Understanding customer purchasing behavior is essential for improving sales performance, customer satisfaction, and long-term business growth. This project analyzes **3,900 customer purchase transactions** from a retail company to identify shopping patterns, customer segments, and revenue opportunities.

The primary business question addressed in this project is:

> **How can the company leverage customer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?**

The project combines **Python**, **PostgreSQL**, and **Power BI** to build a complete data analytics workflow—from data cleaning and SQL analysis to interactive dashboard development and business recommendations.

---

## 📂 Dataset

The dataset contains **3,900 records** and **18 features** covering customer demographics, purchase information, and shopping behavior.

### Customer Demographics
- Age
- Gender
- Location
- Subscription Status

### Purchase Details
- Item Purchased
- Category
- Purchase Amount (USD)
- Season
- Size
- Color

### Shopping Behavior
- Discount Applied
- Previous Purchases
- Purchase Frequency
- Review Rating
- Shipping Type

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python (Pandas, SQLAlchemy)** | Data cleaning, preprocessing, EDA, and database integration |
| **PostgreSQL** | Data storage and business analysis using SQL |
| **Power BI** | Interactive dashboard and visualization |
| **Gamma** | Presentation creation |
| **Jupyter Notebook** | Data analysis workflow |

---

## 📊 Project Workflow

### 1. Data Loading & Exploratory Data Analysis (EDA)

- Imported the dataset using **Pandas**
- Examined dataset structure
- Checked data types
- Generated descriptive statistics
- Identified missing values and inconsistencies

---

### 2. Data Cleaning & Feature Engineering

Performed several preprocessing tasks including:

- Imputed **37 missing Review Rating values** using the **median rating within each product category**
- Standardized column names using **snake_case**
- Removed redundant columns such as:
  - `promo_code_used`
- Created new features:
  - `age_group`
  - `purchase_frequency_days`

---

### 3. Database Integration

- Connected Python to **PostgreSQL**
- Used **SQLAlchemy** and **psycopg2**
- Loaded the cleaned dataset into PostgreSQL for SQL-based analysis

---

### 4. SQL Business Analysis

Executed analytical SQL queries to answer business questions such as:

- Revenue by gender
- High-spending customers using discounts
- Top 5 highest-rated products
- Shipping type performance comparison
- Customer segmentation
- Category-wise revenue analysis
- Subscription behavior insights

---

### 5. Power BI Dashboard

Designed an interactive dashboard to visualize:

- Overall business KPIs
- Customer demographics
- Revenue distribution
- Category performance
- Subscription analysis
- Age group analysis
- Sales trends

---

### 6. Reporting

Summarized the analysis into:

- Business report
- Interactive Power BI dashboard
- Presentation created using Gamma

---

# 📈 Dashboard Highlights

The dashboard provides an executive overview of retail performance.

### Key Performance Indicators (KPIs)

| Metric | Value |
|---------|------:|
| Total Customers | **3.9K** |
| Average Purchase Amount | **$59.76** |
| Average Review Rating | **3.75** |
| Subscribers | **27%** |
| Non-Subscribers | **73%** |

### Dashboard Visualizations

- Revenue by Category
- Revenue by Age Group
- Subscription Analysis
- Sales Distribution
- Product Performance
- Customer Segmentation
- Shipping Type Analysis

---

## 💡 Key Insights

- Clothing generates the highest sales volume.
- Subscribers contribute significantly to recurring purchases.
- Certain discount campaigns attract high-value customers.
- Top-rated products consistently generate stronger sales.
- Express shipping customers tend to spend more on average.
- Middle-aged customer groups contribute the largest share of revenue.

---

# 🚀 Business Recommendations

Based on the analysis, the following strategies are recommended:

### Increase Subscription Adoption

- Promote exclusive subscriber benefits
- Offer loyalty discounts
- Provide early access to new products

### Build Customer Loyalty

- Introduce a rewards program
- Incentivize repeat purchases
- Target occasional shoppers with personalized offers

### Optimize Discount Strategy

- Evaluate profitability of discount-heavy products
- Reduce unnecessary discounting
- Focus promotions on high-margin products

### Promote Best-Selling Products

- Feature top-rated products in marketing campaigns
- Increase visibility of high-performing categories
- Cross-sell complementary products

### Targeted Marketing

- Focus campaigns on high-revenue age groups
- Personalize offers using customer segmentation
- Promote express shipping to premium customers

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git
```

Navigate to the project directory:

```bash
cd customer-shopping-behavior-analysis
```

Install the required dependencies:

```bash
pip install pandas sqlalchemy psycopg2-binary
```

---

# ▶️ How to Run

### 1. Run the Jupyter Notebook

Open:

```
Customer_Shopping_Behavior_Analysis.ipynb
```

This notebook will:

- Load the dataset
- Clean the data
- Perform feature engineering
- Export the cleaned dataset
- Upload data into PostgreSQL

---

### 2. Execute SQL Queries

Run the SQL scripts in PostgreSQL (or pgAdmin) to reproduce the business analysis.

---

### 3. Open the Power BI Dashboard

Open the `.pbix` file using **Power BI Desktop** to explore the interactive dashboard.

---

# 📸 Dashboard Preview

> *(Add your Power BI dashboard screenshot here)*

```markdown
![Dashboard Preview](images/dashboard_preview.png)
```

---

# 📌 Future Improvements

- Customer Lifetime Value (CLV) prediction
- RFM Customer Segmentation
- Recommendation System
- Sales Forecasting using Machine Learning
- Customer Churn Prediction
- Automated ETL Pipeline
- Deployment using Streamlit or Power BI Service

---

# 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL Analytics
- Database Integration
- Data Visualization
- Business Intelligence
- Dashboard Development
- Business Recommendation
- Data Storytelling

---

## ⭐ If you found this project useful, consider giving it a star!
```
