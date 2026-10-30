# Customer Behavior Analysis | Python, SQL & Power BI

## 1. Project Overview

This project focuses on analyzing customer shopping behavior to understand purchasing patterns, customer preferences, spending habits, and subscription trends.

The objective is to explore customer data using Python, perform business-focused SQL analysis using PostgreSQL, and develop an interactive Power BI dashboard to present meaningful insights.

This project demonstrates an end-to-end data analytics workflow, from raw data exploration to business intelligence and visualization.

## 2. Dataset

**Dataset Name:** Customer Shopping Behavior

**File:** `customer_shopping_behavior.csv`

**Dataset Size:** 3,900 rows and 18 columns.

The dataset contains customer shopping information, including:

- Customer demographics (Age, Gender, Location)
- Purchased products and categories
- Purchase Amount
- Review Ratings
- Subscription Status
- Shipping Type
- Discounts and Promo Codes
- Previous Purchases
- Payment Methods
- Purchase Frequency

## 3. Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Data visualization |
| Jupyter Notebook | Python development |
| PostgreSQL | Database management |
| SQL | Business data analysis |
| Power BI | Interactive dashboard |
| Git & GitHub | Version control |

## 4. Project Workflow

### Step 1: Data Loading – Python

- Imported the dataset using Pandas.
- Examined the first few records.
- Checked dataset dimensions and column names.
- Reviewed data types and statistical summaries.

### Step 2: Exploratory Data Analysis (EDA)

- Analyzed customer demographics.
- Explored product categories and purchasing patterns.
- Examined purchase amounts and review ratings.
- Identified missing values.
- Studied customer subscription and shopping frequency.

### Step 3: Data Cleaning & Preparation

- Handled missing review ratings using category-wise mean imputation.
- Standardized column names.
- Created age groups using customer age.
- Created a purchase frequency mapping.
- Removed the unnecessary promo code column.
- Prepared the dataset for SQL analysis.

### Step 4: SQL Analysis – PostgreSQL

Connected Python to PostgreSQL and loaded the prepared dataset into the database.

Performed 10 business-focused SQL analyses:

1. Revenue comparison between male and female customers.
2. Customers using discounts while spending above average.
3. Top 5 products based on average review ratings.
4. Average purchase amount by shipping type.
5. Spending comparison between subscribers and non-subscribers.
6. Products with the highest discount usage percentage.
7. Customer segmentation into new, returning, and loyal customers.
8. Top 3 purchased products within each category.
9. Subscription behavior among repeat customers.
10. Revenue contribution by age group.

SQL concepts used include:
- SELECT, WHERE, GROUP BY
- ORDER BY and LIMIT
- Aggregate functions
- CASE statements
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- JOIN operations where applicable

### Step 5: Power BI Dashboard

Developed an interactive dashboard to visualize customer shopping behavior.

Dashboard components include:

- Customer and purchase KPIs
- Average purchase amount
- Subscription status analysis
- Product category performance
- Customer distribution by age group
- Purchase amount by age group
- Interactive filters for gender, category, shipping type, and subscription status

## 5. Dashboard Preview

The Power BI dashboard provides an interactive view of customer purchasing patterns and business performance.

**Dashboard Screenshot:**

![Customer Behavior Dashboard](images/customer_behaviour_dashboard.png)

*Replace this image with your actual Power BI dashboard screenshot.*

## 6. Key Results & Business Insights

The analysis is designed to answer important business questions:

- Which customer groups contribute more to purchase revenue?
- Do subscribers spend more than non-subscribers?
- Which products receive the highest customer ratings?
- How effective are discounts in influencing purchases?
- Which product categories perform best?
- How do purchasing patterns differ across age groups?
- Are repeat customers more likely to subscribe?

**Important Findings:**

Add 3–5 actual findings from your completed SQL queries and Power BI dashboard here.

## 7. How to Run the Project

### Prerequisites

Install the following tools:

- Python 3.x
- Jupyter Notebook
- PostgreSQL
- pgAdmin (optional)
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/customer-behavior-analysis.git
```

### Step 2: Navigate to the Project

```bash
cd customer-behavior-analysis
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary jupyter
```

### Step 4: Run Python Notebook

```bash
jupyter notebook
```

Open:

`customer_shopping_behavior_analysis.ipynb`

Run the notebook cells in sequence.

### Step 5: Configure PostgreSQL

- Create a PostgreSQL database.
- Update the database connection settings securely.
- Run the notebook section that loads the cleaned dataset into PostgreSQL.

### Step 6: Execute SQL Queries

Open `customer_behaviour_sql.sql` in pgAdmin or another PostgreSQL SQL editor and execute the analysis queries.

### Step 7: Open Power BI Dashboard

Open `customer_behaviour_dashboard.pbix` using Power BI Desktop.

Configure the data source if required and refresh the data.

## 8. Project Structure

```text
customer-behavior-analysis/
│
├── dataset/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── customer_shopping_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behaviour_sql.sql
│
├── dashboard/
│   └── customer_behaviour_dashboard.pbix
│
├── images/
│   └── customer_behaviour_dashboard.png
│
├── requirements.txt
├── .gitignore
└── README.md
```

## 9. Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Python Data Analysis
- PostgreSQL Database Management
- SQL Business Analysis
- Data Visualization
- Power BI Dashboard Development
- Customer Segmentation
- Business Intelligence
- Analytical Problem Solving

## 10. Author

Pranav Shinde

BSc IT Graduate | Aspiring Data Analyst



*This project was developed as part of my hands-on learning journey in Data Analytics.*

⭐ If you find this project useful, feel free to explore the repository.
