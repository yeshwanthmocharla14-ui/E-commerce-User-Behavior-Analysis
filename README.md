# 🛒 E-Commerce User Behavior Analysis

## 📌 Project Overview

This is an end-to-end Data Analytics project focused on analyzing customer purchasing behavior, revenue trends, payment preferences, delivery performance, and return analysis using SQL, Python, and Power BI.

The objective of this project is to understand how customers interact with an e-commerce platform and generate actionable business insights through data analysis and visualization. The project simulates a real-world business scenario where companies analyze user behavior to improve customer experience, sales performance, and business decision-making.

In this project, I performed:
- Data Cleaning
- SQL Business Analysis
- Exploratory Data Analysis (EDA)
- Data Visualization
- Interactive Dashboard Development
- Business Insight Generation

---

# 🎯 Project Objectives

The main goals of this project are:

- Analyze customer purchasing behavior
- Identify top-performing product categories
- Understand payment method preferences
- Analyze return behavior and delivery performance
- Track revenue trends over time
- Generate business insights from customer data
- Build an interactive Power BI dashboard

---

# 🛠️ Tools & Technologies Used

| 🔧 Tool / Technology | 📌 Purpose |
|---|---|
| 🗄️ SQL (MySQL) | Data querying and business analysis |
| 🐍 Python | Data cleaning and exploratory analysis |
| 🐼 Pandas | Data manipulation and preprocessing |
| 🔢 NumPy | Numerical operations |
| 📈 Matplotlib | Data visualization |
| 🎨 Seaborn | Statistical visualization |
| 📊 Power BI | Dashboard development |
| 💻 VS Code | Python & SQL development |
| 📑 Jupyter Notebook | Interactive data analysis |
| 🌐 GitHub | Project hosting and version control |

---

# 📂 Dataset Information

### Dataset Used:
E-Commerce Customer Behavior Dataset

### Dataset Columns

| Column Name | Description |
|---|---|
| order_id | Unique order identifier |
| customer_age | Age of customer |
| customer_gender | Gender of customer |
| product_category | Product category |
| payment_method | Payment method used |
| order_value_usd | Total order value |
| delivery_time_days | Delivery duration |
| customer_rating | Customer review rating |
| returned | Return status |
| order_date | Date of order |

---

# 📌 Project Workflow

---

## 1️⃣ Data Collection

- Downloaded dataset from Kaggle
- Imported dataset into MySQL, Python, and Power BI

---

## 2️⃣ Data Cleaning & Preprocessing

Performed multiple data cleaning operations:

- Checked missing values
- Removed duplicate records
- Verified data types
- Converted date columns into datetime format
- Created monthly trend columns for analysis

---

## 3️⃣ SQL Business Analysis

Performed SQL-based business analytics using MySQL.

### SQL Analysis Included:
- Total Revenue Analysis
- Average Order Value
- Revenue by Product Category
- Payment Method Analysis
- Return Analysis
- Gender-based Revenue Analysis
- Monthly Revenue Trends
- Customer Rating Analysis

---

## 📌 Sample SQL Query

```sql
SELECT product_category,
       SUM(order_value_usd) AS revenue
FROM ecommerce_user_behavior
GROUP BY product_category
ORDER BY revenue DESC;
```

🐍 Python Exploratory Data Analysis (EDA)

Performed Exploratory Data Analysis using Python libraries such as Pandas, Matplotlib, and Seaborn.

📊 Analysis Performed
Revenue Analysis
Monthly revenue trends
Category-wise revenue
Customer Behavior Analysis
Gender-based purchasing trends
Customer rating analysis
Business Performance Analysis
Return analysis
Delivery performance analysis
Payment method usage
Correlation Analysis
Relationship between delivery time, ratings, and order value

📌 Sample Python Code
```
monthly_revenue = df.groupby('month')['order_value_usd'].sum()

monthly_revenue.plot(marker='o')

plt.title("Monthly Revenue Trend")

plt.xlabel("Month")

plt.ylabel("Revenue")

plt.show()
```

📊 Power BI Dashboard

Developed an interactive and professional Power BI dashboard to visualize customer behavior and business performance.

Dashboard Features
KPI Cards
Total Revenue
Total Orders
Average Customer Rating
Average Delivery Time
Interactive Charts
Monthly Revenue Trend
Revenue by Product Category
Payment Method Usage
Return Analysis
Revenue by Gender
Customer Rating Distribution
Delivery Time vs Customer Rating
Filters/Slicers
Product Category
Gender
Payment Method
Return Status

📌 Dashboard Preview

(Add your dashboard screenshot here)

📈 Key Business Insights

The following business insights were identified through analysis:

✅ Electronics category generated the highest revenue

✅ Credit Card was the most used payment method

✅ Faster deliveries resulted in better customer ratings

✅ Returned orders negatively impacted revenue

✅ Certain customer segments contributed higher purchasing value

📁 Project Structure
Ecommerce_User_Behavior_Analysis/
│
├── data/
├── sql/
├── python/
├── dashboard/
├── reports/
├── screenshots/
└── README.md
🚀 Skills Demonstrated

This project demonstrates practical skills in:

SQL querying
Data Cleaning
Exploratory Data Analysis
Business Analytics
Dashboard Development
Data Visualization
Customer Behavior Analysis
Business Storytelling
📚 Learning Outcomes

Through this project, I gained practical experience in:

End-to-end Data Analytics workflow
SQL business analysis
Python-based EDA
Interactive dashboard creation
Business insight generation
Data-driven decision making
📷 Screenshots

(Add screenshots of:

Power BI Dashboard
Python Charts
SQL Analysis)
🔮 Future Improvements

Possible future enhancements include:

Customer segmentation using machine learning
Predictive analytics
Revenue forecasting
Real-time dashboard integration
Recommendation system implementation

📌 Conclusion

This project successfully demonstrates the complete workflow of a Data Analytics project starting from data collection and cleaning to business analysis, visualization, dashboard development, and insight generation.

The project helped strengthen practical skills in SQL, Python, Power BI, and business storytelling while improving analytical thinking and problem-solving abilities.

👨‍💻 Author
Yeshwanth

Aspiring Data Analyst 

Skilled in SQL, Python, Power BI, and Data Analytics
Interested in Customer Analytics and Business Intelligence
