Customer Shopping Behavior Analysis
📌 Project Overview
This project focuses on analyzing customer shopping behavior using transactional data of 3,900 purchases across multiple product categories. The objective is to extract meaningful insights into customer preferences, spending patterns, and business performance to support data-driven decision-making.

📊 Dataset Details
Total Records: 3,900
Features: 18 columns
Includes:
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Product, Category, Amount, Season, Size, Color)
Behavioral data (Discount usage, Purchase frequency, Ratings, Shipping type)
Data Cleaning: Handled missing values in review ratings using median imputation

🐍 Data Processing (Python)
Data cleaning and preprocessing using Pandas
Handled missing values and standardized column names
Feature engineering:
Created age groups
Derived purchase frequency metrics
Removed redundant columns
Loaded cleaned data into PostgreSQL for further analysis

🗄️ Data Analysis (SQL)
Performed business-focused analysis including:

Revenue comparison by gender
High-spending customers using discounts
Top-rated and best-selling products
Subscriber vs non-subscriber behavior
Shipping type impact on spending
Customer segmentation (New, Returning, Loyal)
Revenue contribution by age group

📈 Dashboard (Power BI)
Developed an interactive Power BI dashboard to visualize:

Sales trends
Customer segmentation
Product performance
Revenue insights

💡 Key Insights & Recommendations
Encourage subscription-based models for higher revenue
Implement loyalty programs for repeat customers
Optimize discount strategies to maintain profit margins
Focus marketing on high-value customer segments
Promote top-rated products for better conversions

🛠️ Tech Stack
Python (Pandas, NumPy)
SQL (PostgreSQL)
Power BI
