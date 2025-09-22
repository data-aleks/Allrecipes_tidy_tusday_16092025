# Allrecipes - Tidy Tuesday - 16.09.2025
This week we're exploring a curated collection of recipes collected from Allrecipes.com! The data this week comes from the tastyR package (a dataset assembled from Allrecipes.com) and was prepared for analysis in R. Fields have been cleaned and standardized where possible to make comparisons and visual exploration straightforward.

A collection of recipe datasets scraped from https://www.allrecipes.com/, containing two complementary datasets: allrecipes with 14,426 general recipes, and cuisines with 2,218 recipes categorized by country of origin. Both datasets include comprehensive recipe information such as ingredients, nutritional facts (calories, fat, carbs, protein), cooking times (preparation and cooking), ratings, and review metadata. All data has been cleaned and standardized, ready for analysis.

Thank you to [Brian Mubia](https://github.com/owlzyseyes) for curating this week's dataset.

## Dataset
* **Source** [Allrecipes](https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2025/2025-09-16/all_recipes.csv)
* **Source** [Cuisines](https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2025/2025-09-16/cuisines.csv)

## Tech Stack
* `pandas`
* `np`
* `matplotlib`
* `seaborn`
* `math`
* `power bi`

## Question
- How does the average fast food breakfast compare to a healthy homemade diet?

## Key Steps

1. **Data Sources**
2. **Project Goals**
3. **Step 1. Loading data**
4. **Step 2. Exploring data**
    -   Important functions
    -   2.1 Data Summary
    -   2.2 Sample Rows
    -   2.3 Missing Data
    -   2.4 Column Properties
    -   2.5 Column Distribution
    -   2.6 Multivariate Correlation
5. **Step 3. Cleaning data**
    -   3.1 Identify Grain, Measure and dimensions
    -   3.2 Identify Critical and Non Critical columns
    -   3.3 Identify Solvable and Non Solvable issues
6. **Step 4. Export data**


## Project Goals
This week we will be working with a new and exiting dataset, the goal is to not answer the questions in the challenge, but to create our own question and also create a compelling visualisation. The main goal is for me to keep improving at story telling. I also want to refine project structure and work on the improving my workflow in python by creating templates so i have to spend less time on organisational side of things and focus on working with the data. 

## Step 1. Loading
## Step 2. Exploring
After looking through data we have identified missing values, which columns pose greater value for the analysis. And generally how the data looks from it descriptive, distribution perspective etc. We quickly identified correlation between caloric content, and negative correlation between caloric content and servings

![Correlation Heatmap: Allrecipes](img\screenshots\all_recipes_correlation_matrix.png "Correlation Matrix")  

![Missing Values: Allrecipes](img\screenshots\all_recipes_missing_values.png "Missing Values")  

## Step 3. Cleaning

## Dashboard Creation