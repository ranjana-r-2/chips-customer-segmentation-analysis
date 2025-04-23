Chips Customer Segmentation Analysis
Overview
This project supports analyze customer purchasing behavior in the chip category. The goal is to assist the supermarket's Category Manager in understanding customer segments and driving strategic planning for the next six months.

The analysis involves cleaning transaction and customer data, segmenting customers, identifying trends, and visualizing purchasing behavior.

Objectives
Data Cleaning: Identify and resolve inconsistencies, null values, and outliers in transaction and customer data.

Exploratory Data Analysis: Visualize transaction patterns, product characteristics (brand, pack size), and purchasing trends.

Customer Segmentation: Analyze purchasing behavior by lifestage and premium customer status.

Sales Analysis: Assess total sales, unit quantities, and price sensitivity across customer groups.

Statistical Testing: Use t-tests to evaluate pricing behavior differences between segments.

Insights and Recommendations: Identify target customer segments for marketing and product strategies.

Dataset
QVI_transaction_data.csv: Contains transactional information such as product name, quantity, sales, and customer ID.

QVI_purchase_behaviour.csv: Contains demographic information including lifestage and premium status of customers.

Key Steps
Load & Inspect Data
Read and explore transaction and customer datasets using pandas.

Clean Data

Convert date fields.

Remove non-chip items (e.g., salsa).

Handle outliers in product quantity.

Extract and standardize brand and pack size data.

Visualizations

Transaction trends over time.

Lifestage distribution.

Sales and customer metrics segmented by demographics.

Average units and price per customer segment.

Merge & Analyze
Combine transaction and customer data, then perform segment-level analysis.

Statistical Testing
Conduct t-tests to compare price sensitivity among different customer groups.

Recommendations
Identify key customer segments (e.g., mainstream young couples) for targeted marketing.

Technologies Used
Python
Libraries: pandas, numpy, matplotlib, seaborn, scipy

Outputs
Cleaned datasets (CSV)

Visualizations (PNG/Plots)

Summary statistics and customer insights

Recommendations for strategic decision-making
