# 👨🏻‍💻 Customer Shopping Behavior Analysis | Data Analyst Portfolio Project

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories. It explores spending patterns, customer segments, product preferences, discount usage, shipping choices, and subscription behavior to support data-driven business decisions.

## 📌 Project Overview

The objective is to translate raw shopping data into useful business insights through the following stages:

✅ **Data Preparation, Modeling & Exploratory Data Analysis (Python):** Clean and transform the raw dataset, handle missing values, and create analysis-ready features.

✅ **Data Analysis (SQL):** Use PostgreSQL queries to investigate customer segments, loyalty, product ratings, discount usage, shipping preferences, and revenue patterns.

✅ **Visualization & Insights (Power BI):** Build an interactive dashboard to present key customer and sales trends.

✅ **Reporting & Presentation:** Summarize the findings and communicate business recommendations through a project report and presentation.

## 🧰 Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- MYSQL
- Power BI

## 📊 Dataset Overview

- **Total purchase records:** 3,900
- **Original columns:** 18
- **Missing values:** 37, all in the `Review Rating` column
- **Data includes:** Customer demographics, products and categories, purchase amount, season, discounts, shipping type, review ratings, subscription status, and previous purchases.

## 🔍 Project Workflow

### 1. Python — Data Preparation & EDA

Notebook: `Customer_Shopping_Behaviour_Analysis.ipynb`

The notebook includes:

- Importing and exploring the dataset using Pandas
- Reviewing data structure and summary statistics
- Handling missing review ratings using the median rating for each product category
- Standardizing column names to `snake_case`
- Creating an `age_group` feature
- Creating a `purchase_frequency_days` feature
- Checking the relationship between discount and promo-code fields
- Loading the cleaned data into PostgreSQL for analysis

**To get started:**
1. Place the raw dataset, `customer_shopping_behavior.csv`, in the project directory.
2. Install the required packages:
3. Open the notebook in Jupyter and run the cells in order.


### 2. SQL — Business Analysis

SQL file: `customer_behavior_sql_queries.sql`

The SQL analysis addresses these business questions:

1. What is the revenue breakdown by gender?
2. Which customers use discounts and still spend above the average purchase amount?
3. Which five products have the highest average review ratings?
4. How does average purchase amount compare between Standard and Express shipping?
5. How do average spend and total revenue differ by subscription status?
6. Which products have the highest percentage of discounted purchases?
7. How many customers fall into New, Returning, and Loyal segments?
8. What are the top three products in each category?
9. How many repeat buyers have more than five previous purchases, split by subscription status?
10. How much revenue does each age group contribute?

**To run the SQL analysis:**
1. Create a MYSQL database.
2. Load the cleaned dataset into a table named `customer`.
3. Open `customer_behavior_sql_queries.sql` in MYSQL.
4. Run the queries and review the result sets.

Make sure the table and column names match those used in the SQL script.

### 3. Power BI — Interactive Dashboard

Dashboard file: `customer_behavior_dashboard.pbix`

Open the `.pbix` file in Power BI Desktop. The dashboard presents customer behavior using KPI cards, charts, and filters, including:

- Number of customers
- Average purchase amount
- Average review rating
- Subscription status
- Revenue and sales by category
- Revenue and sales by age group
- Filters for subscription status, gender, category, and shipping type


### 4. Project Report & Presentation

Supporting project files:

- `Business Problem Document.pdf`
- `Customer Shopping Behavior Analysis.pdf`
- `Customer-Shopping-Behavior-Analysis.pptx`

These documents describe the business problem, analytical process, findings, and recommendations.

## 💡 Key Insights Explored

- Revenue contribution by gender and age group
- High-spending customers who use discounts
- Products with strong review ratings
- Differences in purchase amounts by shipping type
- Subscriber and non-subscriber purchasing patterns
- Products with high discount usage
- New, Returning, and Loyal customer segments
- Popular products within each category

## 🚀 Business Recommendations

- **Boost subscriptions:** Test exclusive benefits that encourage sign-ups and retention.
- **Build customer loyalty:** Reward repeat purchases and encourage customers to move from New to Returning and Loyal segments.
- **Review discount effectiveness:** Evaluate discounts against revenue and profit margins.
- **Promote popular products:** Highlight highly rated and frequently purchased products in relevant campaigns.
- **Use targeted marketing:** Tailor campaigns to customer groups and validate performance with measurable results.
- **Review shipping options:** Compare customer spend with shipping costs before expanding express-shipping promotions.



## 🛠️ How to Use This Project

1. **Clone the repository**

   ```bash
   git clone https://github.com/SumaHari/customer-trends-data-analysis-SQL-Python-PowerBI.git
   cd customer-trends-data-analysis-SQL-Python-PowerBI
   ```

2. **Run the Python notebook**  
   Open `Customer_Shopping_Behaviour_Analysis.ipynb`, provide the raw CSV file, configure your database connection, and run the notebook cells.

3. **Run the SQL queries**  
   Load the prepared data into PostgreSQL and execute `customer_behavior_sql_queries.sql`.

4. **Open the Power BI dashboard**  
   Open `customer_behavior_dashboard.pbix`, configure the data source if required, and refresh the dashboard.

5. **Review the report and presentation**  
   Use the PDF report and PowerPoint presentation to understand the findings and business recommendations.


## 👨‍💻 About the Author

I am Suma S aspiring Data Analyst transitioning from software testing with 4.10 years experience .with hands-on in collecting, analyzing, and validating raw data from multiple sources while ensuring integrity for business decisions. Proficient in Python, SQL, Excel, Power BI, and data preprocessing tools, passionate about transforming data into actionable insights for process optimization 


