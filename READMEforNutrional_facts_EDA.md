Internship Task 01 for CodeX Techno: Exploratory Data Analysis on Food Nutrition Dataset

This project performs an Exploratory Data Analysis (EDA) on a food nutrition dataset containing details such as food items, calories, fat and other nutritional values. 
The main goal is to identify distributions, detect outliers and uncover meaningful insights about calorie content and nutritional patterns.
<br>DATASET LINK: https://www.kaggle.com/datasets/mcdonalds/nutrition-facts<br>
1. DATASET DESCRIPTION

Total rows: 260<br>
Total columns: 8<br>
Missing values: None<br>
Duplicates: None<br>
Consistency: All categorical values appear consistent<br>

1.2 DATA TYPES

Numeric: Calories, Protein, Carbohydrates, Total Fat and Sugar.
Categorical: Item, Category<br>
Datetime: None<br>

1.3 BASIC STATISTICS

Average calories per item: 310 kcal<br>
Median calories: 280 kcal<br>
Range of calories: 50 – 950 kcal<br>
Average protein per item: 12 g<br>
Average fat per item: 9 g<br>

2. ANALYSIS WORKFLOW

2.1 DATA OVERVIEW:

Checked dataset shape, column names and types.<br>
Verified no missing or duplicate values.<br>
Identified variation in calorie content across categories.<br>


2.2 VARIABLE EXPLORATION:

Numeric variables: summarized mean, median, standard deviation.<br>
Categorical variables: counted items per category.<br>
Outlier detection: Boxplots and IQR method used to identify calorie outliers.<br>


2.3 DATA VISUALIZATION:

Histograms: calorie distribution, fat distribution.<br>
Boxplots: detected calorie outliers (items above ~650 kcal).<br>
Bar charts: compared calorie averages across categories.<br>
Heatmap: correlation between calories, fat, sugar and protein.<br>

3. INSIGHTS

3.1 Nutritional Patterns:

Majority of food items fall between 200–400 calories.<br>
Outliers include high-calorie fast foods (>700 kcal).<br>
Protein content is positively correlated with calories.<br>
Drinks and desserts generally have higher sugar but lower protein.<br>

3.2 Outlier Analysis:

Outliers identified above 650 kcal are mostly burgers, fried foods and combos.
Low-calorie outliers (<100 kcal) are mostly salads and beverages.

3.3 Category Trends:

Burgers and Combos contribute most to calorie-heavy items.<br>
Salads and Drinks are consistently lower in calories.<br>
Snacks and Desserts show the widest calorie spread.<br>


4. RECOMMENDATIONS

The menu could be worked upon to highlight low-calorie items (salads, light drinks) as healthier alternatives.<br>
For calorie-conscious customers,  portion control options for high-calorie categories could be introduced.
Restaurants can promote balanced meals by pairing low-calorie items with higher-protein items.<br>
Outliers (>700 kcal) should be flagged in menus with nutritional warnings.<br>


5. CONCLUSION:

This EDA reveals important insights into calorie distribution and nutritional content of food items. <br>
The analysis highlights outliers, category differences and correlations, which can be used by 
restaurants, nutritionists and customers to make informed dietary choices.<br>
