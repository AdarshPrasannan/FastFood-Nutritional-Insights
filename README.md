## 🍔 Fast-Food Nutrition Analysis 

This project analyzes a comprehensive fast-food nutrition dataset to understand calorie density, nutrient composition, company-wise differences, and category-level health impacts across major fast-food chains.


## 📘 Project Overview

Fast-food consumption is rising globally, making nutritional transparency more important than ever.
This project performs an in-depth Exploratory Data Analysis (EDA) of fast-food menu data to uncover:

- How calories, fat, carbs, sugar, sodium, protein, and fiber vary across items

- Nutritional differences between companies

- Category-level patterns (burgers, pizzas, burritos, beverages, etc.)

- Correlations and nutrient interactions

- Classification of items into Low–Mid–High nutrient categories

- Outliers and potential health concerns

The goal is to understand the nutritional landscape of fast-food menus and identify patterns that can guide healthier choices and menu improvements.


## 🎯 Project Objectives

- Load and inspect the raw fast-food nutrition dataset

- Clean messy values, correct datatypes, and remove duplicates

- Engineer additional fields (Food Category, Low/Mid/High nutrient classes)

- Perform univariate, bivariate, and multivariate analysis

- Generate meaningful visualizations using seaborn and matplotlib

- Summarize insights, highlight correlations, and identify outliers

- Export a fully cleaned dataset for future modeling


## 🔑 Key Insights

- Most fast-food items are calorie-dense, falling between 300–600 calories.

- Sodium levels are extremely high, with some items exceeding 2000 mg in a single serving.

- Sugar spikes appear mostly in beverages, desserts, and sweetened items.

- Protein varies widely across chains, especially in meat-based menus.

- Fiber is consistently low, indicating limited vegetables and whole grains.

- Burger King, Wendy’s, and Taco Bell tend to have higher calories and carbs.

- Pizza Hut shows consistently high sodium due to cheese and processed toppings.

- Categories like burgers, burritos, and pizzas dominate calorie, fat, and sodium levels.

- Strong correlations were found:

  - Calories ↔ Total Fat

  - Calories ↔ Sodium

  - Carbs ↔ Sugars

  - Calories ↔ Weight Watchers Points

- Significant outliers exist in sodium (2000+ mg) and sugar (100+ g).

##  🛠 Techniques & Tools Used

- Python (Pandas, NumPy) – data manipulation

- Matplotlib, Seaborn – visualizations

- Feature Engineering – derived nutrient categories

- EDA – univariate, bivariate, multivariate analysis

- Correlation & heatmaps – nutrient relationships

- Data cleaning pipeline – type correction, category extraction, value sanitization
