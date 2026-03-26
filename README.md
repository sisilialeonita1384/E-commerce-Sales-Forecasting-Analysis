# E-commerce-Sales-Forecasting-Analysis

This project analyzes large-scale e-commerce transaction data to understand sales behavior, cancellation patterns, and product demand, then extends the analysis into forecasting future sales using machine learning and time series models.

What I did?

I worked with a dataset of more than 500,000 transactions from a Pakistan-based e-commerce platform (2016–2018) .

The process included:

1. Cleaning the data (handling missing values, removing irrelevant columns)
2. Exploring sales trends and customer behavior
3. Analyzing product demand and cancellation patterns
4. Building and comparing two models:
   - Random Forest Regression
   - Prophet (time series forecasting)
5. Evaluating performance using R², MAE, and MSE

Key insights
- The highest-selling category is mobiles and tablets
- Cancellation rates increase significantly in the last quarter, indicating a strong time-related effect
- Product demand varies across months, showing clear seasonal patterns
- Some categories, such as books and stationery, have stable demand throughout the year
- Random Forest performs better than Prophet for this dataset

Why it matters

This analysis shows that understanding sales alone is not enough. Factors like timing, demand patterns, and cancellations play a critical role in overall performance. By combining analysis and prediction, this project provides a more complete view for decision-making.

Tools: Python (Google Colab)

Output
- Sales and demand analysis
- Cancellation behavior insights
- Forecasting model for future sales trends
