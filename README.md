# Customer Shopping Behavior Analysis

## Project Description
This project analyzes customer sales data using Python (Pandas) and SQL Server Express.
The CSV data is cleaned, stored in a relational database, and analyzed using SQL queries
to generate meaningful business insights.

## Objective
- Clean and preprocess raw CSV data
- Store data in SQL Server Express
- Perform SQL-based data analysis
- Understand customer purchase behavior

## Technologies Used
- Python
- Pandas
- SQL Server Express
- SQL Server Management Studio (SSMS)
- SQLAlchemy
- Jupyter Notebook

## Dataset / Data Content
- File Name: customer_shopping_behavior.csv
- Records: 15
- Data Type: Structured CSV
- Purpose: Customer behavior analysis

### Columns
customer_id, category,age, gender, city, item_purchased, category, quantity,purchased_amount,
price, discount_applied, payment_method, purchase_date

## Project Flow
CSV File → Pandas Data Cleaning → SQL Server Express → SQL Queries → Analysis

## Project Structure
├── data/
│   └── customer_sales_data.csv
├── notebooks/
│   └── data_cleaning.ipynb
├── scripts/
│   └── upload_to_sql.py
├── README.md

## Database Details
- Database: SQL Server Express
- Tool: SSMS
- Table: customer

## How to Run the Project
1. Install libraries: pandas, sqlalchemy, pyodbc
2. Start SQL Server Express
3. Update database credentials
4. Run Python script
5. Execute SQL queries in SSMS

## Sample SQL Query
SELECT category, SUM(quantity) AS total_sales
FROM customer_sales_data
GROUP BY category;

## Output / Results
- Promote Subscription Plans
- Introduce Loyalty Programs
- Optimize Discount Strategy
- Discount impact analyzed

## Future Enhancements
- Add Power BI dashboard
- Automate ETL pipeline
- Add REST API

## Author
Ashish Sharma  
MCA | Python | SQL | Data Analysis
