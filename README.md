# Customer Shopping Behavior Analysis

## Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases across multiple product categories**.  
The objective is to uncover insights related to **customer spending patterns, product preferences, discount usage, and subscription behavior** to support data-driven business decisions.

The project follows an **end-to-end data analysis workflow** using:
- **Python (Pandas, Jupyter Notebook)** for Exploratory Data Analysis (EDA)
- **PostgreSQL** for SQL-based business insights
- **Power BI** for interactive dashboard visualization

---

## Dataset
The dataset contains **3,900 rows and 18 columns** covering:

- Customer demographics: Age, Gender, Location
- Purchase information: Item Purchased, Category, Purchase Amount, Season
- Shopping behavior: Discount Applied, Promo Code Used, Purchase Frequency
- Customer engagement: Review Rating, Subscription Status
- Order details: Shipping Type, Size, Color

Missing values in the **Review Rating** column were handled during preprocessing.

---

## Project Workflow

### 1. Data Cleaning & EDA (Python)
Using **Pandas in Jupyter Notebook**:
- Loaded and explored the dataset
- Handled missing values using **median imputation**
- Standardized column names (snake_case)
- Created new features:
  - **age_group**
  - **purchase_frequency_days**
- Performed exploratory analysis to understand distributions and patterns

---

### 2. SQL Analysis (PostgreSQL)
Cleaned data was loaded into **PostgreSQL** to perform analytical queries and derive business insights.

Key analyses included:
- Revenue comparison by **gender**
- Identification of **high-spending discount users**
- **Top-rated products** based on customer reviews
- **Shipping type impact** on purchase amount
- **Subscriber vs non-subscriber revenue comparison**
- Products with the **highest discount dependency**
- **Customer segmentation** (New, Returning, Loyal)
- **Top products per category**
- Revenue contribution by **age group**

---

### 3. Data Visualization (Power BI)

An interactive **Power BI dashboard** was built to visualize key metrics and insights.

Dashboard highlights include:
- Total customers
- Average purchase value
- Average product rating
- Revenue by category
- Revenue by age group
- Sales by category
- Customer distribution by subscription status

Filters allow exploration by:
- Gender
- Category
- Shipping type
- Subscription status

---

## Key Insights
- Male customers generated significantly higher total revenue compared to female customers.
- A large portion of customers fall into the **loyal customer segment**, indicating strong repeat purchase behavior.
- Certain products show **high discount dependency**, suggesting promotional pricing influences demand.
- Younger and middle-aged customer groups contribute significantly to revenue.
- Express shipping customers tend to have slightly higher purchase amounts.

---

## Business Recommendations
- Promote **subscription benefits** to increase customer retention.
- Introduce **loyalty programs** for repeat buyers.
- Optimize **discount strategies** to balance sales and profit margins.
- Highlight **top-rated products** in marketing campaigns.
- Target **high-revenue age groups** with personalized marketing.

---

## Tech Stack
- **Python**
- **Pandas**
- **Jupyter Notebook**
- **PostgreSQL**
- **SQL**
- **Power BI**

---
