# Walmart_Project
Objective:
This project aims to analyze Walmart's weekly sales data and develop predictive models to forecast sales for the next 12 weeks. The analysis involves statistical analysis, exploratory data analysis (EDA), outlier analysis, handling missing values, and various predictive modeling techniques.

Steps Followed:
Statistical Analysis and EDA: Conducted statistical analysis to gain insights into the data.
Performed EDA to understand the distribution of variables and relationships.

Data Visualization: Utilized visualizations to represent patterns, correlations, and trends in the data.
Investigated the impact of various factors on weekly sales through visualization.

Predictive Modeling:
a. Linear Regression: R2 Score: 0.1641 MSE Score: 270,519,048,713.93 RMSE: 520,114.46
b. Decision Tree: R2 Score: 0.9204 MSE Score: 25,768,665,056.10 RMSE: 160,526.21
c. Random Forest: R2 Score: 0.9530 MSE Score: 15,198,328,551.10 RMSE: 123,281.50
d. KNN: R2 Score: 0.4891 MSE Score: 165,346,663,650.69 RMSE: 406,628.41
e. XGBoost: R2 Score: 0.0890 MSE Score: 289,288,446,863.84 RMSE: 537,855.41

Summary Statistics and Statistical Tests: Calculated correlation between Weekly Sales and Unemployment Rate.
Performed a t-test comparing Weekly Sales between two groups (Group_A and Group_B).
T-Statistic: -2.03
P-Value: 0.0425

Time Series Analysis: Applied time series analysis to identify seasonal trends in weekly sales. Analyzed the impact of variables on weekly sales using scatter plots.

Store Ranking and Top-Performing Stores: Aggregated weekly sales data by store and calculated total sales. Ranked the stores based on historical sales to identify top-performing stores.

Predictive Modeling (Random Forest): Split the dataset into training and testing sets. Implemented Random Forest Regressor.Evaluated the model's performance using MSE: 303,464,742,634.46.

Conclusion and Recommendations:
Insights: The unemployment rate has a significant impact on weekly sales in certain stores. Seasonal trends exist, with specific periods showing increased sales.
Temperature, Consumer Price Index, and Fuel Price also influence weekly sales.

Store Performance: Identified top-performing stores and the worst-performing stores.Observed a significant difference between the highest and lowest-performing stores.

Predictive Modeling: Random Forest showed the best performance among the models. XGBoost had lower predictive power, suggesting other factors may influence sales.

Recommendations: Monitor and manage inventory based on seasonal trends. Consider store-specific strategies for managing sales during high unemployment periods.

Future Work: Explore more advanced predictive modeling techniques. Investigate external factors impacting sales (e.g., economic indicators).Continuous monitoring and updating of models for accurate forecasting.
