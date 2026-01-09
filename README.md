# zomato-data-analysis-project-
Zomato Restaurant Data Analysis

This project provides a basic exploratory data analysis (EDA) of Zomato restaurant data, using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The analysis includes understanding restaurant types, votes, ratings, online ordering trends, and more.

# Dataset

The dataset used is Zomato-data-.csv, containing information about restaurants including:

name: Name of the restaurant

online_order: Whether online ordering is available (Yes/No)

book_table: Whether table booking is available (Yes/No)

rate: Average rating of the restaurant

votes: Number of votes received

approx_cost(for two people): Approximate cost for two people

listed_in(type): Type of cuisine

Dataset size: 148 rows × 7 columns

#Libraries Used

Pandas: For data manipulation

NumPy: For numerical operations

Matplotlib: For basic plotting

Seaborn: For advanced visualization

# Analysis Performed
1. Data Overview

Displayed first few rows of the dataset using head()

Checked data types and non-null counts with info()

Verified missing values using isnull().sum()

2. Restaurant Type Analysis

Count of restaurants by type using sns.countplot()

Total votes by restaurant type using groupby() and plot()

3. Most Voted Restaurant

Identified the restaurant with maximum votes:

#Empire Restaurant

4. Online Order Availability

Count of restaurants offering online orders using countplot()

5. Ratings Analysis

Distribution of ratings visualized using a histogram

Comparison of ratings for online vs offline orders using a boxplot

6. Order Mode Preference by Restaurant Type

Created a pivot table for online order availability vs restaurant type

# Visualized with a heatmap

Visualizations

Count Plot of restaurant types

Line Plot of total votes per restaurant type

Histogram of rating distribution

Boxplot comparing online vs offline ratings

Heatmap showing order mode preference by restaurant type
