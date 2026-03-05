# Jobaaj_Learning_Projects_Python_SQL_Project
This README provides a comprehensive overview of the **Navigating the Future of Online Shopping** project, which combines Python-based exploratory data analysis and advanced SQL querying to extract business insights from an e-commerce dataset.

---

# Navigating the Future of Online Shopping: E-commerce Data Analysis

## 📌 Project Overview

This project aims to analyze customer behavior, sales trends, and operational performance for an online retail platform. By leveraging both **Python** for data exploration and visualization and **SQL** for complex data retrieval and KPI calculation, the project provides a holistic view of the "online shopping" landscape.

## 🗂️ Project Structure

* **Navigating_the_future_of_Online_Shopping.ipynb**: A Jupyter Notebook (Google Colab) that performs Exploratory Data Analysis (EDA) and data cleaning.
* **Jobaaj_NAVIGATING THE FUTURE OF ONLINE SHOPPING.sql**: A collection of SQL scripts categorized into basic, intermediate, and advanced levels to solve real-world business problems.

## 🛠️ Technologies Used

* **Python**: Pandas, NumPy, Matplotlib.
* **SQL**: MySQL (Advanced Window Functions, CTEs, and Aggregations).
* **Platform**: Google Colab / Jupyter Notebook.

## 📊 Key Analysis & Features

### 1. Python Exploratory Data Analysis (EDA)

The notebook processes a dataset containing over **99,000 customers** across various states. Key steps include:

* **Data Cleaning**: Handling null values and assessing data types.
* **Demographic Analysis**: Visualizing customer distribution by city and state (e.g., high concentration in "SP" - Sao Paulo).
* **Statistical Summaries**: Calculating mean and distribution metrics for customer zip codes and locations.

### 2. SQL Business Logic & KPIs

The SQL script is designed to answer critical questions across three complexity levels:

* **Basic**: Total sales per category, percentage of installment payments, and order counts for specific years (e.g., 2017).
* **Intermediate**: Monthly order trends in 2018, average products per order by city, and total revenue segmented by quarter and state.
* **Advanced**:
* **Customer Retention**: Calculating the percentage of customers who made a second purchase within 6 months.
* **Financial Growth**: Computing Year-over-Year (YoY) revenue growth.
* **Cumulative Performance**: Tracking cumulative sales over time to monitor platform growth.
* **Top Spenders**: Identifying the top 3 customers with the highest spending each year.



## 📈 Sample Findings

* **Payment Behavior**: A significant portion of orders are paid via installments, indicating a preference for flexible payment options among users.
* **Retention Trends**: The analysis calculates the retention rate to help understand customer loyalty.
* **Category Leadership**: Identification of top-selling product categories to inform inventory management.

## 📖 How to Use

1. **Python Analysis**: Open the `.ipynb` file in Google Colab or Jupyter. Ensure the required datasets (`customers.csv`, `orders.csv`, etc.) are available in the specified directory.
2. **SQL Analysis**: Import the `.sql` script into your MySQL environment. The queries are designed to run against a schema named `jobaaj`.

---

*This project serves as a portfolio piece for retail data analytics, demonstrating proficiency in data manipulation and strategic insight generation.*
