# Sales-Data-Analysis-Customer-Segmentation-and-churn-prediction
This project performs sales data analysis, focusing on customer segmentation and churn prediction.

This project delves into sales data to uncover insights into customer behavior, segment customer groups, and predict churn. It employs a comprehensive approach, from data preprocessing and exploratory analysis to advanced RFM (Recency, Frequency, Monetary) segmentation and robust churn prediction modeling.

## Project Overview
The core objectives are to analyze sales performance across regions and products, categorize customers based on their purchasing habits, and build predictive models to identify customers at risk of churn. This work provides actionable insights for sales strategies and customer retention efforts.

## Dataset
The project utilizes a sales transaction dataset (sales_superstore.csv.zip) containing vital information such as order details, customer demographics, product categories, and sales figures. Initial data checks confirmed the dataset's integrity, with minor handling for missing postal codes and conversion of date fields for time-based analysis.

## Key Insights:
Geographic Sales Performance: Analysis reveals that while the West region generates the most orders, the South and East regions exhibit higher mean sales per order. Specific states like Wyoming and Virginia, and cities like Jamestown, stand out for their significant mean sales.

## Product Performance:
Technology products lead in mean sales, followed by Furniture, with Office Supplies having the lowest. Within sub-categories, Copiers and Machines are top performers. "Staples" is identified as the most frequently purchased product.

## Sales Trends: 
An overall upward trend in sales is observed over the four-year period (2015-2018), with notable sales spikes during year-end holidays and mid-year promotions.

## Customer Segmentation (RFM):
Customers are segmented into 'Loyal', 'Potential', 'Needs Attention', and 'At Risk' categories based on their Recency, Frequency, and Monetary scores. The analysis shows a healthy customer retention rate of approximately 80.45%, indicating strong customer loyalty.

## Churn Prediction: 
Several machine learning models were developed to predict customer churn. The XGBoost Classifier achieved an impressive 92.44% accuracy, the Random Forest Classifier a 94.96% accuracy, and Logistic Regression 94.12% accuracy, demonstrating the effectiveness of RFM features in churn prediction.
