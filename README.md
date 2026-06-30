# Customer Segmentation Analysis using Machine Learning & Power BI

A portfolio project that segments customers based on purchasing behavior and demographics using Python (Scikit-learn) and visualizes actionable business insights with Power BI.
## Project Overview

Customer segmentation is one of the most important techniques in customer analytics. It helps businesses identify groups of customers with similar characteristics and purchasing behaviors, enabling personalized marketing strategies and better business decisions.
In this project, customer data was cleaned, transformed, and analyzed using Python. K-Means Clustering was then applied to segment customers into meaningful groups. Finally, an interactive Power BI dashboard was created to present business insights and recommendations.

## Project Objectives
Clean and preprocess customer data

Perform exploratory data analysis (EDA)

Engineer meaningful customer features

Segment customers using K-Means Clustering

Analyze purchasing behavior and campaign responses

Visualize customer segments in Power BI

Generate business recommendations for each customer segment

## Dataset Information

The dataset contains customer demographic details, income, purchasing history, and marketing campaign responses.
| Attribute            | Value   |
| -------------------- | ------- |
| Original Records     | 2,240   |
| Processed Records    | 2,216   |
| Original Features    | 29      |
| Final Features       | 39      |
| Missing Values       | Handled |
| Duplicate Records    | Removed |
| Clustering Algorithm | K-Means |
| Number of Clusters   | 4       |


## Tools & Technologies

| Tool             | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Data Cleaning & Analysis  |
| Pandas           | Data Manipulation         |
| NumPy            | Numerical Operations      |
| Matplotlib       | Data Visualization        |
| Seaborn          | Statistical Visualization |
| Scikit-learn     | K-Means Clustering        |
| Power BI         | Interactive Dashboard     |
| Jupyter Notebook | Development Environment   |

## Project Workflow

Data Collection
       │
       ▼
Data Cleaning
       │
       ▼
Feature Engineering
       │
       ▼
Exploratory Data Analysis (EDA)
       │
       ▼
Feature Scaling
       │
       ▼
K-Means Clustering
       │
       ▼
Customer Segmentation
       │
       ▼
Business Insights
       │
       ▼
Power BI Dashboard

## Data Cleaning

The following preprocessing steps were performed:

Removed duplicate records
Handled missing values
Corrected data types
Converted dates into datetime format
Detected and analyzed outliers
Standardized column names

## Feature Engineering

New features were created to improve customer analysis.

Feature	Description
Customer_Age	Age calculated from Year_Birth
Family_Size	Total family members
Total_Spending	Total amount spent across all product categories
Total_Purchases	Total purchases from all channels
Customer_Tenure	Years since customer enrollment

## Exploratory Data Analysis

The project includes:

Age Distribution
Income Distribution
Spending Distribution
Education Analysis
Marital Status Analysis
Income vs Spending
Age vs Spending
Income vs Purchases
Correlation Heatmap
Campaign Acceptance Analysis
Product Preference Analysis
## Customer Segmentation

K-Means Clustering was used to segment customers based on:

Income
Customer Age
Total Spending
Total Purchases
Family Size

Feature scaling was applied using StandardScaler before clustering.

The optimal number of clusters was determined using:

Elbow Method
Silhouette Score
## Customer Segments
**Cluster 0 – Older Low-Value Customers**

Characteristics:
Moderate Income
Older Customers
Low Spending
Few Purchases
Low Campaign Response

Business Strategy:
Discount Coupons
Loyalty Points
Reminder Emails
Re-engagement Campaigns

**Cluster 1 – Affluent Loyal Customers**

Characteristics:
High Income
High Spending
Frequent Purchases
Good Campaign Acceptance

Business Strategy:
VIP Membership
Personalized Recommendations
Premium Product Bundles
Loyalty Rewards

**Cluster 2 – Premium High-Value Customers**

Characteristics:
Highest Income
Highest Spending
Highest Purchase Frequency
Highest Campaign Response

Business Strategy:
Premium Membership
Luxury Products
Early Access to New Products
Personalized Marketing
Customer Retention Programs

**Cluster 3 – Budget Customers**

Characteristics:
Lowest Income
Lowest Spending
Least Purchases
Price Sensitive

Business Strategy:
Discount Offers
Cashback
Bundle Deals
Seasonal Promotions
## Power BI Dashboard

**The dashboard includes:**

Executive Dashboard
Total Customers,
Average Income,
Average Spending,
Average Purchases,
Campaign Response Rate,
Customer Demographics,
Age Distribution,
Education Analysis,
Marital Status,
Family Size Distribution,
Customer Segmentation,
Cluster Distribution,
Income by Cluster,
Spending by Cluster,
Purchases by Cluster,
Scatter Plot (Income vs Spending),
Marketing Insights,
Campaign Acceptance,
Product Preferences.
Cluster-wise Business Recommendations
## Key Business Insights
Premium customers generate the highest revenue and should be retained through exclusive rewards.
Loyal customers respond well to personalized marketing campaigns.
Budget-conscious customers are highly influenced by discounts and promotional offers.
Older low-value customers require re-engagement strategies to improve retention.
Customer segmentation enables targeted marketing, improving campaign effectiveness and customer satisfaction.
## Project Structure
Customer-Segmentation-Analysis/
│
├── data/
│   ├── customer_data.csv
│   └── customer_segmentation_final.csv
│
├── notebooks/
│   └── Customer_Segmentation_Analysis.ipynb
│
├── powerbi/
│   └── Customer_Segmentation_Dashboard.pbix
│
├── images/
│   ├── dashboard.png
│   ├── clusters.png
│   └── correlation_heatmap.png
│
├── README.md
└── requirements.txt
## Results
Successfully segmented customers into four meaningful groups.
Identified high-value customers for targeted marketing.
Improved understanding of customer purchasing behavior.
Developed an interactive Power BI dashboard for business decision-making.
## Future Improvements
Compare K-Means with DBSCAN and Hierarchical Clustering.
Build customer lifetime value (CLV) prediction models.
Integrate RFM analysis with clustering.
Deploy the project as an interactive web application using Streamlit.
## Author

Ankan Chowdhury

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning








