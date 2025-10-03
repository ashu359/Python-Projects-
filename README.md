SK Electronic Shop Performance Analysis

📋 Project Overview
This project analyzes sales data for SK Electronics, a local electronic shop, to understand sales patterns, customer behavior, and product performance. The analysis helps identify revenue-generating products, seasonal sales trends, and factors influencing customer satisfaction.

🎯 Problem Statement
SK Electronics faces challenges in:

Identifying which products generate the most revenue

Understanding how seasonal changes affect sales

Determining factors that influence customer satisfaction

A comprehensive analysis is required to make better business decisions, increase sales, and improve customer service.

📊 Dataset Information

The dataset contains 1,550 sales transactions with 23 columns including:

Key Features:
Invoice Details: Invoice_ID, Date, Product, Category, Brand, Quantity, Unit_Price, Total_Amount

Customer Information: Customer_Age, Customer_Gender, Customer_City, Region, Country

Sales Channel: Online vs Store purchases

Financial Details: Discount (%), Final_Amount, Warranty_Period

Product Information: Product_Manufacture_Date

Customer Feedback: Customer_Satisfaction_Rating (1-5 scale)

Time Features: Year, Month (extracted from Date)

🔧 Data Cleaning Process

Handling Missing Values:
Customer_Satisfaction_Rating: Filled with median value

Discount (%): Replaced NaN with "No Discount"

Region: Filled NaN values with "None"

Feature Engineering:
Extracted Year and Month from Date for time-based analysis

📈 Key Findings

1. Revenue Trends by Year
2022: ₹75,691,767

2023: ₹177,924,556

Significant growth in revenue from 2022 to 2023

2. Top 5 Products by Revenue
Laptop: ₹65,305,277

Camera: ₹56,779,441

TV: ₹44,544,852

Mobile: ₹31,190,479

Tablet: ₹27,280,066

3. Data Statistics Summary
Average Transaction: ₹163,623

Average Customer Age: 42 years

Average Quantity per Transaction: 5.5 units

Average Customer Satisfaction: 2.96/5

🛠️ Technical Implementation

Libraries Used:
pandas - Data manipulation and analysis

numpy - Numerical computations

seaborn - Statistical data visualization

matplotlib - Plotting and visualization

Analysis Performed:
Data loading and initial exploration

Data cleaning and preprocessing

Basic statistical analysis

Revenue analysis by year and product

Data visualization using bar charts

📊 Visualizations

The analysis includes visual representations of:

Total sales by year (bar chart)

Top 5 products by revenue (bar chart)

💡 Business Insights

Revenue Growth:
The shop experienced substantial revenue growth from 2022 to 2023

2023 revenue more than doubled compared to 2022

Product Performance:
Laptops and Cameras are the highest revenue-generating products

All top 5 products show strong market performance

Customer Experience:
Average customer satisfaction rating is below average (2.96/5)

This indicates room for improvement in customer service

🚀 Recommendations

Focus on High-Performing Products:

Increase inventory and marketing for Laptops and Cameras

Consider bundling popular products

Improve Customer Satisfaction:

Investigate reasons for low satisfaction ratings

Implement customer feedback systems

Train staff on customer service

Seasonal Strategy:

Analyze monthly trends to optimize inventory

Plan promotions around high-sales periods

Discount Strategy:

Analyze impact of discounts on sales and customer satisfaction

Optimize discount percentages for maximum profit

🔮 Future Analysis Potential

Customer segmentation analysis

Regional sales performance

Payment method preferences

Warranty period impact on sales

Seasonal trend analysis

Customer lifetime value calculation

👥 Target Audience

Shop owners and managers

Business analysts

Marketing teams

Inventory managers

Customer service teams

This analysis provides a solid foundation for data-driven decision making at SK Electronics, helping the business optimize operations and improve customer satisfaction.
