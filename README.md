Internship Task 01 for CodeX Techno: Exploratory Data Analysis on Food Nutrition Dataset

This project performs an Exploratory Data Analysis (EDA) on a food nutrition dataset containing details such as food items, calories, fat, and other nutritional values. 
The main goal is to identify distributions, detect outliers, and uncover meaningful insights about calorie content and nutritional patterns.

1. DATASET DESCRIPTION

Total rows: 260
Total columns: 8
Missing values: None
Duplicates: None
Consistency: All categorical values appear consistent

1.2 DATA TYPES

Numeric: Calories, Protein, Carbohydrates, Total Fat, Sugar
Categorical: Item, Category
Datetime: None

1.3 BASIC STATISTICS

Average calories per item: 310 kcal
Median calories: 280 kcal
Range of calories: 50 – 950 kcal
Average protein per item: 12 g
Average fat per item: 9 g

2. ANALYSIS WORKFLOW

2.1 DATA OVERVIEW:

Checked dataset shape, column names, and types.
Verified no missing or duplicate values.
Identified variation in calorie content across categories.


2.2 VARIABLE EXPLORATION:

Numeric variables: summarized mean, median, standard deviation.
Categorical variables: counted items per category.
Outlier detection: Boxplots and IQR method used to identify calorie outliers.


2.3 DATA VISUALIZATION:

Histograms: calorie distribution, fat distribution.
Boxplots: detected calorie outliers (items above ~650 kcal).
Bar charts: compared calorie averages across categories.
Heatmap: correlation between calories, fat, sugar, and protein.

3. INSIGHTS

3.1 Nutritional Patterns:

Majority of food items fall between 200–400 calories.
Outliers include high-calorie fast foods (>700 kcal).
Protein content is positively correlated with calories.
Drinks and desserts generally have higher sugar but lower protein.

3.2 Outlier Analysis:

Outliers identified above 650 kcal are mostly burgers, fried foods, and combos.
Low-calorie outliers (<100 kcal) are mostly salads and beverages.

3.3 Category Trends:

Burgers and Combos contribute most to calorie-heavy items.
Salads and Drinks are consistently lower in calories.
Snacks and Desserts show the widest calorie spread.


4. RECOMMENDATIONS

The menu could be worked upon to highlight low-calorie items (salads, light drinks) as healthier alternatives.
For calorie-conscious customers,  portion control options for high-calorie categories could be introduced.
Restaurants can promote balanced meals by pairing low-calorie items with higher-protein items.
Outliers (>700 kcal) should be flagged in menus with nutritional warnings.


5. CONCLUSION:

This EDA reveals important insights into calorie distribution and nutritional content of food items. 
The analysis highlights outliers, category differences, and correlations, which can be used by 
restaurants, nutritionists,and customers to make informed dietary choices.
