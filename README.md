#  Amazon Sales Data Analysis (EDA Project)
## Project Overview
This project involves performing Exploratory Data Analysis (EDA) on an e-commerce dataset similar to Amazon. The goal is to understand sales performance, customer purchasing behavior, product trends, and estimated profitability. The analysis was carried out using Python, with insights communicated through visualizations and clear explanations.

# Problem Statement
Management wants to understand key aspects of business performance, including:
- Overall sales performance  
- Sales trends over time  
- Product category and regional performance  
- Customer purchasing behavior  
- Profitability patterns  
However, the dataset does not include cost or profit data, requiring estimation for deeper analysis.

# Objectives
- Clean and prepare the dataset  
- Analyze sales and quantity trends  
- Evaluate performance across categories and regions  
- Understand customer purchasing behavior  
- Estimate profit using assumptions  
- Communicate insights effectively  

# Tools & Technologies
- Python  
- pandas  
- matplotlib  
- seaborn  
- Jupyter Notebook  

# Data Cleaning
- Checked for missing values and duplicates  
- Converted `order_date` to datetime format  
- Ensured numeric columns were correctly formatted  

# Assumptions
Since cost and profit were not provided:

- Cost was calculated as  
- Total Cost = quantity sold * price
- Profit = total cost - total revenue
> Note: These are calculated values and may not reflect actual business profitability.

# Analysis Performed
- Overall Sales Performance  
- Sales Trend Over Time  
- Category Performance  
- Regional Performance  
- Profitability Analysis  
- Customer Purchasing Behavior  
- Correlation Analysis  

# Key Insights
- The business generated approximately **$32.87M in revenue**  
- Sales remained **stable over time**  
- Categories contributed **evenly to total revenue**  
- Profit margins appeared **uniform (~15%) due to assumptions**  
- Customer purchasing behavior was **evenly distributed (1–5 items)**  
- Strong relationship between **quantity, revenue, and profit**  

# Business Implications
- Stable sales indicate predictable performance  
- Uniform profitability limits deeper insights  
- Balanced category performance shows diversification  
- Customer behavior insights are limited due to data pattern  

# Recommendations
- Collect actual cost data for accurate profit analysis  
- Improve data realism for better behavioral insights  
- Focus on increasing sales volume  
- Introduce bundles or promotions to increase order size  
- Monitor trends regularly  

# Conclusion
This analysis provides a clear overview of sales and business performance. However, limitations such as estimated profit and uniform customer behavior highlight the importance of accurate and realistic data for deeper insights.

AUTHOR

Johnson Modinat
