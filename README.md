# Olist-E-Commerce-Data-Analysis
End-to-end Brazilian e-commerce data analysis using Python, Excel, and Power BI to uncover sales, customer, payment, delivery, product, and seller insights.
##  Project Overview

This project analyzes the Brazilian E-Commerce Public Dataset provided by Olist, a Brazilian online marketplace. The dataset contains approximately 100,000 orders placed between 2016 and 2018 across multiple interconnected CSV files.

The objective is to transform raw e-commerce data into meaningful business insights that can help stakeholders understand sales trends, customer purchasing patterns, product performance, and delivery efficiency.

##  Business Objectives

- Analyze sales and revenue trends over time.
- Measure order volume and average order value.
- Understand customer purchasing and repeat purchase behavior.
- Identify top-performing product categories and sellers.
- Analyze payment methods and customer spending patterns.
- Evaluate delivery performance and late deliveries.
- Explore customer review scores and satisfaction.
- Build clear visualizations and business-focused insights to support data-driven decisions.

##  Tools & Technologies

- **Python:** Data analysis and preprocessing
- **Pandas:** Data manipulation, cleaning, merging, and aggregation
- **NumPy:** Numerical operations
- **Matplotlib:** Data visualization
- **Excel:** KPI analysis, reporting, and dashboard development
- **Power BI:** Interactive business intelligence dashboards
- **Jupyter Notebook:** Exploratory data analysis
- **VS Code:** Development environment
- **Git & GitHub:** Version control and project documentation

##  Dataset Description

The project uses the Olist Brazilian E-Commerce Public Dataset, which contains nine CSV files:

| Dataset | Description |
|---|---|
| `olist_orders_dataset.csv` | Order status, purchase timestamps, and delivery dates |
| `olist_order_items_dataset.csv` | Products purchased, prices, freight, and sellers |
| `olist_order_payments_dataset.csv` | Payment methods, installments, and payment values |
| `olist_order_reviews_dataset.csv` | Customer review scores and comments |
| `olist_customers_dataset.csv` | Customer IDs, locations, and unique customer identifiers |
| `olist_products_dataset.csv` | Product categories, dimensions, and attributes |
| `olist_sellers_dataset.csv` | Seller identifiers and locations |
| `olist_geolocation_dataset.csv` | Geographic coordinates and Brazilian postal-code locations |
| `product_category_name_translation.csv` | Portuguese-to-English product category translations |

**Data source:** [Olist Brazilian E-Commerce Public Dataset — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset is anonymized and represents historical transactions, not live marketplace activity.

##  Project Workflow

### 1. Data Loading and Exploration
- Imported CSV files into Python using Pandas.
- Examined dataset dimensions, column names, and data types.
- Reviewed missing values, duplicate records, and data quality.
- Identified relationships between orders, customers, products, payments, sellers, and reviews.

### 2. Data Cleaning and Preparation
- Handled missing values where appropriate.
- Converted date and time columns into appropriate datetime formats.
- Checked duplicate records and inconsistent values.
- Merged related datasets using appropriate identifiers.
- Prepared analysis-ready tables for business analysis.

### 3. Exploratory Data Analysis (EDA)
- Analyzed order volume and revenue trends.
- Examined customer purchase behavior.
- Evaluated product category and seller performance.
- Investigated payment preferences.
- Analyzed delivery timelines and review scores.

### 4. Excel Analysis
- Organized and summarized key business metrics.
- Evaluated sales and customer KPIs.
- Prepared reporting tables and visual summaries.

### 5. Power BI Dashboard
- Presented business KPIs and trends through interactive visualizations.
- Organized insights around sales, customers, products, and delivery performance.
- Designed reports to make findings easier for business stakeholders to understand.

## 📊 Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Orders | 99,441 |
| Unique Customers | 96,096 |
| Total Revenue | R$ 13,591,643.70 |
| Average Order Value | R$ 136.68 |
| Repeat Customers | 2,997 |
| Repeat Customer Rate | 3.12% |
| Delivered Orders | 96,478 |
| Cancelled Orders | 625 |
| Sellers | 3,095 |
| Customers from São Paulo (SP) | 41,746 |

*Note: Revenue and average order value are expressed in Brazilian reais (R$). KPI definitions depend on the relevant dataset tables and filters. The repeat customer rate is based on the project's customer-level calculation.*

##  Key Business Insights

### 1. Customer Purchasing Behavior
The analysis identified 96,096 unique customers and 2,997 repeat customers, representing a repeat customer rate of approximately 3.12%. This highlights an opportunity to investigate customer retention, loyalty programs, and repeat-purchase strategies.

### 2. Sales Performance
The dataset contains 99,441 orders and approximately R$13.59 million in order-item revenue. These metrics provide a baseline for evaluating sales performance, order value, and changes in purchasing activity over time.

### 3. Geographic Distribution
São Paulo was the leading customer state, with 41,746 customer records. This indicates a significant concentration of marketplace activity in São Paulo and provides a basis for geographic sales and customer analysis.

### 4. Delivery Performance
The project examined order statuses, estimated delivery dates, and actual delivery timestamps to understand delivery efficiency. These metrics can help identify late deliveries and opportunities to improve logistics.

### 5. Product and Seller Performance
Product and order-item data support comparisons of category revenue, sales volume, and seller performance. These comparisons help identify strong-performing categories and sellers.

### 6. Payment and Customer Reviews
Payment data enables analysis of payment preferences and installment behavior, while review data supports investigation of customer satisfaction and potential relationships between delivery experience and review scores.

##  Business Recommendations

- Investigate why repeat purchasing is relatively low and identify opportunities to improve customer retention.
- Monitor monthly revenue, order volume, and average order value to identify changes in sales performance.
- Evaluate delivery delays and their potential relationship with customer review scores.
- Identify high-performing product categories and sellers to guide business planning.
- Review payment preferences to understand customer purchasing behavior.
- Use KPI dashboards to monitor performance and support operational decisions.

These recommendations are based on the types of patterns examined in the dataset; further analysis would be needed to establish causes and quantify the impact of proposed actions.

##  Project Structure

```text
olist-ecommerce-data-analysis/
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── Olist_Ecommerce_Analysis.ipynb
│
├── excel/
│   └── Olist_Analysis.xlsx
│
├── powerbi/
│   └── Olist_Dashboard.pbix
│
├── visualizations/
│   └── dashboard_preview.png
│
├── requirements.txt
└── README.md
```

*This is the suggested repository structure. Keep only files and folders that you have actually created, and update filenames to match your repository.*

**Dataset note:** The original CSV files are not included in this suggested structure because the dataset is available from Kaggle. The `data/README.md` file can explain how to download and place the files locally.

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis
- Data manipulation using Pandas and NumPy
- Data merging and relational analysis
- KPI calculation and business reporting
- Sales and customer analytics
- Data visualization
- Dashboard development
- Business insight generation
- Analytical problem-solving

## How to Run the Project

1. Download the Olist dataset from Kaggle.
2. Extract the CSV files into the project's local data folder.
3. Install the required Python libraries.
4. Open the Jupyter Notebook in VS Code or Jupyter Notebook.
5. Run the notebook cells in sequence.
6. Open the Excel workbook to explore the KPI analysis.
7. Open the Power BI file in Power BI Desktop to explore the dashboard, if included.

Install the Python dependencies using:

```bash
pip install pandas numpy matplotlib jupyter
```

Additional libraries can be added to `requirements.txt` if the notebook uses them.

Learning Outcomes

Through this project, I developed practical experience in:

- Working with multiple related datasets.
- Cleaning and preparing real-world transactional data.
- Performing exploratory data analysis with Python.
- Calculating and interpreting business KPIs.
- Analyzing customer behavior and operational performance.
- Translating data findings into business recommendations.
- Presenting analytical results through reporting and visualization tools.

## Author

**Sanika Jadhav**

PGDM in Business Analytics | Aspiring Data Analyst
