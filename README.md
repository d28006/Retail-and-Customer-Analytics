![Preview](https://github.com/d28006/Customer-Segmentation/blob/main/Snapshot.png)
1. Project Title / Headline

Customer Segmentation Analysis: Identifying Target Groups for Marketing Strategy
A clustering-driven market segmentation analysis designed to uncover distinct customer groups based on income, age, and spending behavior—empowering the marketing team to target the right customers with tailored campaigns.

2. Short Description / Purpose

The Customer Segmentation project applies unsupervised learning (K-Means clustering) to identify meaningful shopping groups within the customer base. By analyzing age, annual income, and spending scores, the project helps the marketing team design personalized strategies that maximize customer engagement, improve campaign ROI, and align promotions with customer behavior patterns.

3. Tech Stack

The analysis was performed using the following tools and technologies:

•  Python (Pandas, NumPy) – Data preprocessing, aggregation, and analysis
•  Matplotlib & Seaborn – Data visualization (distributions, correlations, cluster visualization)
•  Scikit-Learn (KMeans) – Unsupervised clustering algorithm to segment customers
•  Jupyter Notebook – Interactive environment for iterative analysis and storytelling
•  File Format – Input CSV dataset, exported processed clusters to CSV/Excel for reporting

4. Data Source

Source: Customer shopping dataset (includes demographic and behavioral features).

The dataset includes:

Age (years)

Annual Income (k$)

Spending Score (1–100) – assigned by the mall based on purchasing behavior

Gender (for additional segmentation analysis)

5. Features / Highlights

Business Problem
Marketing teams need to understand customer segments to design tailored promotional strategies. Without clear segmentation, campaigns risk being too broad and ineffective.

Goal of the Analysis
To identify key customer clusters by analyzing their income, age, and spending habits, enabling data-driven targeting and positioning.

6. Walkthrough of Key Analysis

 Distribution Plots → Visualized how age, income, and spending scores vary by gender.

 Correlation Analysis → Checked relationships between spending score, income, and age.

 K-Means Elbow Method → Determined the optimal number of customer clusters (k).

 Cluster Profiling → Computed mean age, income, and spending score for each cluster.

 2D Scatter Visuals → Displayed clear groupings of high-income vs high-spending vs budget-conscious customers.

7. Business Impact & Insights

 Cluster 1: Young High Spenders → Younger age group, moderate-to-high income, very high spending scores. Ideal target for luxury and lifestyle marketing.

 Cluster 2: Middle-Aged Budget Customers → Moderate income, low-to-mid spending scores. Better suited for promotions and discounts.

 Cluster 3: High-Income Low Spenders → Older demographic, high income, but low spending score. Upselling and premium loyalty campaigns can unlock value here.

 Cluster 4: Balanced Shoppers → Mid-age, mid-income, balanced spending scores. Represents a stable customer base for mainstream products.

 Cluster 5: Affluent Enthusiastic Shoppers → Younger-to-mid-age group, high income, and very high spending scores. Strong candidates for premium product launches, luxury campaigns, and personalized high-end marketing.

 Strategic Takeaway → By focusing campaigns differently for each cluster, the marketing team can maximize ROI, reduce wasted spend, and improve customer retention.
