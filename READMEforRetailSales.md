# codeX_techno
Internship task 01 for CodeX Techno

This project performs an Exploratory Data Analysis on a retail sales dataset containing 1000 transactions. The dataset includes customer demographics, product details, and sales amounts. The goal of this analysis is to uncover patterns in customer behaviour, sales trends, and product performance.

1.DATASET DESCRIPTION:

Total rows:1000
Total columns:9
Missing values: none
Duplicates: none
Consistency; all categorical values appear consistent


1.2 DATA TYPES:
Numeric: quantity, age, Transaction ID, price per unit,total amount
Datetime: date
Categorical: gender, product category, customer ID

1.3 BASIC STATISTICS:
Average transaction amount:₹456
Average customer age; 41
Average items per transactions: 2.5
Average unit price per products sold: 179

ANALYSIS WORKFLOW:

1. DATA OVERVIEW:
   Checked dataset structure, data types and missing values.
   Verified all columns have non-null values.
   Identified skewness in total amount due to a few high-vaue traansactions.
   
2.VARIABLE EXPLORATION

Numeric variables: examined distributions, mean, mdian, standard deviation.
Categorical variables; counted transactions per category and gender.
Age group analysis: customers categorized into teens, young adults, adult, seniors.


3. DATA VISUALIZATION:

Histograms and Boxplots : identified outliers and spread of numerical data.
Bar charts were used to plot: frequency of transactions by product category, age group and gender
Heatmaps: correlation between numerical variables.


4. INSIGHTS:

Customer Behaviour:

 1. Most transactions are between 1-4 items.
 2. Gender distribution is roughly balanced; slightly more females(510 transactions vs 490         males).
 3. Quantity purchased correlates strongly with total amount spent; gender has negligible        effect for the same quantity.

Product Trends:  

 1. Clothing is the most purchased category; all three categories (clothing, electronics,           beauty) are well represented.
 2. Electronics gennerate the highest total revenue due to higher transaction values despite       lower average spend per purchase.
 3. Beauty products have the highest average spend per transaction(~₹467).
      
Spending Patterns:

  1. A few high-value trasactions skew total revenue.
  2. Men spend more per purchase on beauty products, even though women buy more frequently.

Temporal Trends:

  1. Monthly Revenue: peaks in May, December and October 2023; drops in January, March, and         September.
  2. Weekly Revenue: Saturdays generate the highest revenue; Thursdays being the lowest.

Age Group Insights:
  1. Young Adults(19-35) are the largest revenue contributors, espeially in clothing and         beauty.
  2. Seniors contribute most in electronics, while teens contribute minimally.

Recommendation:

  Target promotions toards young adults for clothing and beauty products.
  Introduce premium product offerings for adults and seniors.
  Plan marketing campaigns  during high-revenue months (May, October, December).
  Boost midweek sales (such as on Thursdays) with targeted promotions.
  
CONCLUSIONS:
This EDA provides a detailed understanding of customer demographics, product performance and sales trends. Insights from this analysis can guide marketting strategies, inventory management and revenue optimization in this retail business.
