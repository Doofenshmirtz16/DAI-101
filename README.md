# DAI-101

Assignment-1

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on an IMDb movie dataset, aiming to uncover insights about movie trends, financial performance, and critical reception. The analysis includes data cleaning, statistical tests, and visualizations to explore relationships between variables.

📂 Dataset

The dataset contains information about 3,348 movies, including:

Numerical features: Budget, Gross revenue, Ratings, Number of Votes, Runtime

Categorical features: Genre, Directors, Release Date

🔍 Analysis Performed

1️⃣ Data Cleaning

Handling missing values in budget, gross, and release_date
Converting release_date to datetime format
Dropping irrelevant columns (if any)

2️⃣ Univariate Analysis

Distribution of numerical variables (Budget, Gross, Runtime, Ratings)
Boxplots, Violin plots, and KDE plots to detect outliers and skewness

3️⃣ Bivariate Analysis

Correlations: Heatmaps of numerical features
Scatter plots: Budget vs Gross, Ratings vs Votes
Director-based insights: Top earning directors, Director vs Genre
Genre analysis: Revenue differences across genres

4️⃣ Statistical Tests

Shapiro-Wilk Test → Check if budget is normally distributed
T-Test → Compare ratings of high-budget vs low-budget movies
ANOVA → Test if gross revenue significantly differs across genres
Chi-Square Test → Check dependency between genre and budget category
Correlation Tests → Pearson and Spearman correlation for budget vs gross
