# Store Sales Analysis and Forecasting

## Project Overview
This project involves a comprehensive analysis of store sales data, including data cleaning, exploratory data analysis (EDA), clustering analysis, and forecasting using time series models. The primary goal is to understand the sales patterns, identify key segments, and predict future sales trends.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data](#data)
3. [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
5. [Clustering Analysis](#clustering-analysis)
6. [Sales Forecasting](#sales-forecasting)
7. [Results and Discussion](#results-and-discussion)
8. [Conclusion](#conclusion)

## Data
The dataset used in this project is the "Store Sales Forecasting Dataset" available on Kaggle. It includes information on sales transactions, including dates, product categories, quantities, discounts, and profits.

## Exploratory Data Analysis
EDA was conducted to understand the distribution of sales, identify patterns, and visualize the relationships between different variables. Key steps included:
- Visualizing sales distributions by category and state.
- Analyzing temporal trends in sales data.
- Identifying potential outliers.

## Data Cleaning and Preprocessing
The data was cleaned by:
- Handling missing values and duplicates.
- Correcting data types and standardizing column names.
- Creating new features such as `order_year_month`.

## Clustering Analysis
Clustering analysis was performed to segment the data into meaningful groups based on sales patterns. We used the K-means algorithm and interpreted the resulting centroids:
- **Cluster 0:** High sales and quantities, low discounts.
- **Cluster 1:** Low sales and quantities, low discounts.
- **Cluster 2:** Low sales and quantities, high discounts.
- **Cluster 3:** Very high sales and quantities, slightly lower discounts.

## Sales Forecasting
I utilized the Prophet library to forecast future sales based on historical data. The model was trained on preprocessed data, and forecasts were visualized and analyzed.

## Results and Discussion
The results showed distinct sales patterns across different clusters, and the forecasting model provided insights into future sales trends. Key findings include:
- Significant variation in sales volume across clusters.
- The impact of discounts on sales volume.
- Forecasting accuracy and potential improvements.

## Conclusion
This project demonstrated the importance of data preprocessing, segmentation, and forecasting in understanding sales data. The insights gained can be used to inform business decisions, optimize inventory, and plan marketing strategies.
