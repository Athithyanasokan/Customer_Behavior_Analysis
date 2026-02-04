🛍️ Customer Shopping Behavior Analysis

📌 Overview

This project analyzes customer shopping patterns to identify purchasing trends, customer preferences, and behavioral insights. The analysis uses Python for data processing and EDA, SQL for querying structured data, Power BI for dashboard visualization, and Gamma for reporting and presentation.

The objective of this project is to transform raw customer transaction data into actionable business insights that help improve marketing strategies, customer engagement, and sales performance.

📂 Dataset

The dataset contains customer purchase behavior across various product categories, demographics, and shopping preferences.

Key Features:

Customer Details

Customer ID

Age

Gender

Location

Purchase Information

Item Purchased

Category

Purchase Amount

Purchase Frequency

Previous Purchases

Product Attributes

Size

Color

Season

Customer Engagement

Subscription Status

Promo Code Usage

Discount Applied

Review Rating

Transaction Details

Payment Method

Shipping Type

🛠️ Tools & Technologies
Programming & Analysis

Python

Pandas

NumPy

Matplotlib

Database & Querying

PostgreSQL / MySQL / SQL Server

SQL for business and analytical queries

Visualization & Reporting

Power BI (Interactive Dashboard)

Gamma (Project Presentation & Report)

Development Environment

Jupyter Notebook

VS Code

🔄 Project Workflow
1️⃣ Data Loading

Imported customer shopping dataset using Python.

Verified dataset structure and data types.

2️⃣ Exploratory Data Analysis (EDA)

Analyzed customer demographics.

Studied purchase patterns across product categories.

Evaluated seasonal shopping trends.

Visualized relationships between discounts, subscriptions, and purchase frequency.

3️⃣ Data Cleaning & Transformation

Handled missing and inconsistent values.

Removed duplicates.

Standardized categorical values.

Created derived features for better analysis.

4️⃣ SQL Analysis

Loaded cleaned dataset into relational database.

Performed queries to analyze:

Customer purchase frequency

Category-wise revenue

Subscription impact on purchasing

Seasonal sales trends

Payment and shipping preferences

5️⃣ Dashboard Development (Power BI)

The dashboard provides interactive visualizations including:

Customer Demographics Overview

Category Performance Analysis

Seasonal Purchase Trends

Subscription vs Non-Subscription Comparison

Revenue and Purchase Frequency KPIs

Payment & Shipping Insights

6️⃣ Reporting

Created presentation using Gamma.

Summarized key findings.

Provided business recommendations based on analysis.

📊 Key Insights

Subscription customers tend to purchase more frequently.

Seasonal trends strongly influence clothing purchases.

Promo codes and discounts increase purchase probability.

Certain payment methods are preferred for high-value transactions.

Purchase behavior varies significantly across age groups and locations.

▶️ How to Run the Project
🔧 Prerequisites

Make sure you have:

Python 3.x

Jupyter Notebook or VS Code

SQL Database (PostgreSQL / MySQL / SQL Server)

Power BI Desktop

🚀 Steps to Execute
1. Clone Repository
git clone https://github.com/yourusername/customer-shopping-analysis.git
cd customer-shopping-analysis

2. Install Required Libraries
pip install -r requirements.txt

3. Run Python Notebook
jupyter notebook


Open:

customer_shopping_behavior.ipynb

4. Load Data into Database

Import dataset CSV into SQL database.

Run SQL queries available in:

Customer Shopping Behaviour Analysis.sql

5. Open Power BI Dashboard

Open:

Customer_Behavior.pbix

6. View Report

Open Gamma presentation or exported PDF report.

📁 Project Structure
📦 Customer Shopping Behavior Analysis
 ┣ 📂 data
 ┣ 📂 notebooks
 ┣ 📂 sql
 ┣ 📂 dashboard
 ┣ 📂 reports
 ┣ 📜 customer_shopping_behavior.ipynb
 ┣ 📜 customer_shopping_behavior.csv
 ┣ 📜 Customer Shopping Behaviour Analysis.sql
 ┣ 📜 Customer_Behavior.pbix
 ┗ 📜 README.md

🚀 Future Enhancements

Predictive modeling for customer purchase forecasting

Customer segmentation using clustering

Automated ETL pipeline

Real-time dashboard integration

Recommendation system for personalized product suggestions

👤 Author

Athithyan Asokan
Data Analytics Enthusiast

GitHub: github.com/Athithyanasokan

LinkedIn: linkedin.com/in/athithyanasokan
