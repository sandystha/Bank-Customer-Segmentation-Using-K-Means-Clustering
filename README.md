# Bank-Customer-Segmentation-Using-K-Means-Clustering

Project Overview

This project performs customer segmentation on a bank dataset of 10,000 customers and 13 features to understand customer behavior and provide actionable business insights. Using K-Means clustering, we identified distinct customer segments to improve retention, marketing, and product offerings.

The analysis includes data preprocessing, feature scaling, K-Means clustering, the Elbow method to determine optimal clusters, and segment profiling for business recommendations.

Problem Statement

A bank wants to understand its customer base to:

Identify high-value and low-value customers

Target customers with personalized offers

Optimize retention strategies

Encourage usage of bank products like credit cards

Improve loyalty for long-tenure and high-balance customers

The goal is to segment customers into meaningful groups for tailored recommendations.

Dataset Overview

Number of Customers: 10,000

Number of Features: 13 (including balance, number of products, credit card ownership, tenure, geography, etc.)

Data Source: Bank customer dataset

Methodology

Data Preprocessing

Handle missing values

Encode categorical variables

Scale numerical features using StandardScaler

K-Means Clustering

Applied K-Means to segment customers

Used the Elbow Method to determine the optimal number of clusters

Cluster Profiling

Analyzed clusters by key metrics: balance, products, credit card ownership, tenure, geography

Assigned meaningful labels to each segment

Customer Segments
Cluster	Segment Profile
0	Customers without a credit card
1	High balance, few products, have credit card
2	Low balance, multiple products, have credit card
3	Many products in a short amount of time

Cluster insights derived from K-Means clustering and feature analysis.

Recommendations
Segment	Recommendation
0	Create an entry-level credit card to engage them
1	Retain high-value customers with personalized offers
2	Reward loyal customers with high tenure, especially in France and Spain
3	Encourage usage of products to improve engagement and retention

General Recommendations:

Offer targeted credit card promotions to new or low-product customers

Design loyalty programs for long-tenure customers

Provide location-specific campaigns (France & Spain)

Monitor product adoption trends to increase cross-selling

Insights & Business Value

Identified distinct customer profiles for targeted marketing

Segmented customers to increase retention and satisfaction

Insights can inform credit card offers, rewards programs, and engagement strategies

Demonstrates how data-driven segmentation improves strategic decision-making

Skills Demonstrated

Python: Pandas, NumPy, Matplotlib, Seaborn

Machine Learning: K-Means Clustering, Elbow Method

Data Analysis: Feature scaling, encoding, cluster profiling

Business Analytics: Recommendations based on customer behavior
