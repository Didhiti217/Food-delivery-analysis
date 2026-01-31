This repository contains my Jupyter Notebook submission for the Hackathon
This project analyzes a food delivery dataset by integrating multiple data sources (CSV, JSON, SQL) and deriving actionable business insights.
The main goal is to understand order trends, user behavior, city- and cuisine-wise performance, membership impact, and revenue patterns.
#Data Integration Steps
1.Load CSV Data → Orders data
2.Load JSON Data → User information
3.Load SQL Data → Restaurant information
#Merge Data:
  -Join orders with users on user_id
  -Join orders with restaurants on restaurant_id
  -Join type: Left Join (to retain all orders)
#Final Dataset → final_food_delivery_dataset.csv containing:
 -Order details
 -User information
 -Restaurant information

Tasks Performed on the Dataset:
-Calculated total and average order value
-Analyzed order trends over time (daily, monthly, quarterly)
-Studied user behavior (repeat customers, high-value users)
-Evaluated city-wise and cuisine-wise performance
-Compared membership impact (Gold vs Regular) on orders and revenue
-Identified top-performing restaurants and high-revenue combinations
-Determined seasonality patterns in orders and revenue
