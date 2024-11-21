Amazon Sales Data Analysis Project


Overview

This project focuses on analyzing Amazon's sales data to uncover key patterns, trends, and insights that can help optimize business strategies. Through various analysis techniques such as Exploratory Data Analysis (EDA), clustering, and dimensionality reduction (PCA and t-SNE), we gain insights into sales performance, customer behavior, and the effectiveness of different fulfillment methods. The goal is to provide actionable recommendations that can improve marketing, inventory management, and customer engagement strategies.


Key Objectives

Sales Trend Analysis: Identify seasonal sales spikes and trends during major shopping events like Prime Day, Black Friday, and the holiday season.

Customer Segmentation: Group customers based on purchasing behavior and offer targeted marketing campaigns and personalized offers.

Fulfillment Method Analysis: Examine the impact of different fulfillment methods (FBA vs third-party fulfillment) on sales and customer satisfaction.

Geographic Sales Distribution: Analyze regional sales data to understand location-based preferences and behavior.

Outlier Detection: Identify and manage outliers in the Sales Amount data, which could represent special transactions or bulk purchases.

Sales by Product Category: Visualize and analyze sales distribution across various product categories to understand which categories contribute most to revenue.


Techniques Used

Exploratory Data Analysis (EDA): For data cleaning, missing value handling, and outlier detection.

Clustering: K-Means clustering for customer segmentation based on purchasing behavior.

Dimensionality Reduction: PCA (Principal Component Analysis) and t-SNE (t-Distributed Stochastic Neighbor Embedding) to reduce high-dimensional data to 2D for easier visualization.
Data Visualization: Matplotlib, Seaborn, and Plotly to create visualizations like line plots, boxplots, violin plots, and scatter plots for analyzing the data.


Python Libraries:

Pandas for data manipulation and cleaning.

Seaborn and Matplotlib for static data visualizations.

Plotly for interactive visualizations.

Scikit-learn for machine learning (Clustering, PCA, t-SNE, and preprocessing).


Results

Peak Sales Periods: Identified key sales spikes during Prime Day, Black Friday, and the holiday season.

Customer Segments: Segmented customers into Frequent Buyers, Occasional Shoppers, and Holiday Shoppers.

Fulfillment Performance: Found that FBA products showed higher sales and customer satisfaction compared to third-party fulfillment.

Geographic Trends: Sales in urban areas were higher, with specific regions showing preferences for certain product categories.

Outliers: Detected high-value transactions likely from bulk or corporate purchases.

Category Performance: Dominant product categories like electronics and home goods generated the most revenue.


Tools and Technologies

Python (version 3.x)

Jupyter Notebook for interactive data analysis

Pandas for data manipulation and cleaning

Seaborn and Matplotlib for data visualization

Scikit-learn for machine learning techniques (Clustering, PCA, t-SNE)

Plotly for creating interactive visualizations


Future Work

Predictive Analytics: Build predictive models to forecast future sales trends and customer behavior using machine learning algorithms.

Real-Time Analytics: Incorporate real-time data to adjust strategies dynamically and improve decision-making in real-time.

External Data Integration: Integrate external factors such as economic indicators, competitor data, or global events to improve the analysis.

