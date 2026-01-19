# CUSTOMER-SALES-ANALYSIS-REPORT
Advanced customer sales analysis using pandas  
Developers Arena - Data Science Internship  
Author : Sai Manikanta

---

## Project Overview
This project is part of Week 5: Advanced Data Manipulation with Pandas under the Developers Arena Data Science Internship.
The goal of this project is to analyze customer purchasing patterns and evaluate overall sales performance using advanced data manipulation techniques.

In this project, multiple datasets are combined and analyzed using pandas to uncover insights related to customer behavior, sales trends, and regional performance.
The project demonstrates how raw transactional data can be transformed into meaningful business insights through efficient data processing and visualization.

---

## Project Objective
The main objectives of this project are:
- To analyze customer purchasing behavior using sales data
- To identify top customers based on total revenue
- To perform advanced data manipulation using pandas
- To merge multiple datasets for deeper analysis
- To summarize data using grouping and pivot tables
- To visualize sales trends and customer performance
- To generate actionable insights for business decision-making

---

## Dataset Used

This project uses two datasets to perform customer sales analysis and advanced data manipulation.

1️⃣ sales_data.csv

This dataset contains transactional sales information.

Columns:

- Date – Date of the sales transaction

- Product – Name of the product sold

- Price – Price of a single unit

- Customer_ID – Unique identifier for each customer

- Region – Sales region

- Total_Sales – Total sales amount for the transaction

Purpose:
Used to analyze sales performance, customer purchasing behavior, and sales trends over time.

2️⃣ customer_churn.csv

This dataset contains customer-related information.

Columns:

- CustomerID – Unique customer identifier

- Gender – Customer gender

- Region – Customer region

- Churn_Status – Indicates whether the customer has churned or not

Purpose:
Used to enrich sales data with customer details and analyze customer retention and regional distribution.

---

## Technologies / Tools Used

- Python 3 – Core programming language used for data analysis

- pandas – For data loading, cleaning, merging, grouping, and advanced data manipulation

- matplotlib – For creating professional data visualizations and charts

- Jupyter Notebook – Interactive environment used to perform analysis and present results step by step.

---

## Key Insights

- A small group of customers contributes a significant portion of total revenue, highlighting the importance of customer segmentation.

- Sales performance varies across regions, indicating opportunities for region-specific marketing strategies.

- Monthly sales analysis helps identify seasonal trends and peak sales periods.

- Pivot table analysis provides a clear summary of sales distribution by product and region.

- Combining customer and sales datasets enables deeper insights into customer behavior and purchasing patterns.

---

## How to Run the Project

Follow the steps below to run the project on your local system:

- Install Python 3.x from the official website:
  https://www.python.org

- Install required dependencies:

- pip install -r requirements.txt
  Open Jupyter Notebook:
  jupyter notebook

- Open the notebook file:
  customer_analysis.ipynb

Run all cells from top to bottom to execute the analysis and generate visualizations.
All generated charts will be saved in the visualizations/ folder.

---

## Conclusion

This project successfully demonstrates advanced data manipulation and analysis using pandas.
By merging multiple datasets, performing aggregations, and creating visualizations, meaningful insights were extracted from raw data.

The project highlights how data-driven analysis can support business decision-making by identifying top customers, sales trends, and regional performance.
Overall, this project strengthens practical skills in data analysis, data transformation, and visualization using Python.
