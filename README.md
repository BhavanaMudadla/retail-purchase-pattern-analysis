# retail-purchase-pattern-analysis
Designed and implemented a data warehouse integrating online and offline datasets through ETL workflows to enable efficient data analysis and decision support.

A data-driven retail analytics project that analyzes customer purchasing behavior across both online and offline retail environments using data mining, machine learning, and customer segmentation techniques.
The project extracts actionable business insights, generates product recommendations, identifies customer segments, and designs personalized marketing strategies to improve customer engagement and sales performance.

## Online Retail Analysis:
1. Market Basket Analysis using Apriori Algorithm
2. Association Rule Mining
3. Product Recommendation System
4. Category-Based Advertisement Recommendation
5. Customer Segmentation using RFM Analysis
6. K-Means Customer Clustering

## Offline Retail Analysis:
1. Exploratory Data Analysis (EDA)
2. Customer Behavior Analysis
3. Product Category Prediction using Random Forest
4. Feature Importance Analysis
5. Personalized Coupon Recommendation System
6. Customer-Based Marketing Strategy Generation

## Problem Statement

Retail businesses generate massive amounts of transactional data every day, but much of this data remains underutilized.
This project aims to answer questions such as:
Which products are frequently purchased together? What customer segments exist within the business? Which factors influence purchasing decisions? How can recommendations and discounts be personalized? Which customers should be targeted with marketing campaigns?

### Datasets:

**Online Retail Dataset**
~50,000 transaction records containing:
Invoice Information, Product Details, Purchase Quantity, Customer Information, Transaction Date, Pricing Information

**Offline Shopping Trends Dataset**
~3,500 customer records containing:
Customer Demographics, Product Categories, Purchase Amounts, Seasonal Information, Customer Loyalty Data, Payment Preferences, Purchase Frequency

### Project Architecture:

Online Retail Data → Data Cleaning → Apriori Analysis → Association Rules → Product Recommendations → Advertisement Recommendations

Offline Retail Data → Data Preprocessing → EDA → Random Forest Classification → Feature Importance Analysis → Coupon & Product Recommendations

## Online Retail Analytics

Market Basket Analysis
Used the Apriori Algorithm to identify frequently purchased product combinations and generate association rules for product recommendations.

**Applications:**
- Cross-selling
- Product bundling
- Personalized recommendations
- Store layout optimization

**Advertisement Recommendation**
Products are classified into categories such as Kitchen, Home Decor, Gifts, Toys, Seasonal, and Stationery, and relevant advertisements are displayed based on customer interests.

**Customer Segmentation**
Performed RFM Analysis (Recency, Frequency, Monetary) followed by K-Means Clustering to segment customers into:

## Offline Retail Analytics

**Exploratory Data Analysis**
Analyzed purchasing behavior across:
- Age Groups
- Gender
- Seasons
- Spending Levels
- Customer Types
- Product Categories

**Key Insights:**
- Clothing was the most purchased category.
- Seasonal trends influenced buying behavior.
- Loyal customers showed consistent purchasing patterns.
- Purchase frequency strongly correlated with spending.

**Product Category Prediction**
Built a Random Forest Classifier to predict product categories using customer attributes such as age group, gender, spending level, season, subscription status, discount usage, purchase frequency, and customer type.

**Model Performance:**
 Accuracy: 83–84%

**Feature Importance**
Top factors influencing purchase behavior:
1. Purchase Frequency
2. Season
3. Age Group
4. Spending Level

Behavioral and seasonal factors had a greater impact than promotional factors such as discounts and promo codes.
