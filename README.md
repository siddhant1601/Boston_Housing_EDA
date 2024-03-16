# Boston Housing Data Analysis Project

Welcome to the Boston Housing Data Analysis project repository! This project delves into the Kaggle Boston housing dataset to uncover insights into housing prices in the Boston area.

## Overview

The primary objective of this project is to conduct a comprehensive analysis of the factors impacting housing prices in Boston. Leveraging the Kaggle Boston housing dataset, we aim to explore various features such as crime rates, average number of rooms, proximity to employment centers, and more to gain a deeper understanding of the dynamics of the housing market in the region.

## Analysis

### Dataset

- *Source:* Kaggle
- *Description:* The dataset comprises detailed information collected by the U.S. Census Service regarding housing in the Boston, Massachusetts area. It encompasses a range of attributes including crime rates, average number of rooms, proximity to employment centers, and more, providing a rich source of data for our analysis.

## Questions Explored

### 1. Data Loading:
- Load the Boston Housing dataset into a Pandas DataFrame.
- Display the first 5 rows of the DataFrame.
### 2. Data Exploration: 
- Use Pandas functions to explore the dataset. Find out the number of rows and columns, column names, data types of the columns, summary statistics, and check for missing values.
### 3. Data Manipulation:
- Add a new column to the DataFrame that categorizes the ‘medv’ (median value of owner-occupied homes) column into ‘Low’, ‘Medium’, and ‘High’.
- Replace the ‘chas’ column (Charles River dummy variable) with ‘Yes’ if chas = 1 and ‘No’ if chas = 0.
- Rename the column ‘rm’ to ‘rooms’.
### 4. Data Analysis:
- Find out the average number of rooms (‘rooms’ column) per dwelling for each category of ‘medv’ (Low, Medium, High).
- Find out the percentage of houses that bound the Charles River.
### 5. NumPy Operations: 
- Convert the ‘age’ column from the DataFrame to a NumPy array
- Compute the mean and standard deviation.
- Normalize the array.

## Conclusion

Through rigorous exploration and analysis of the Boston housing dataset, we have gained valuable insights into the intricate relationships between various features and housing prices in the Boston area. Our findings offer a deeper understanding of the factors driving the housing market dynamics, empowering stakeholders to make more informed decisions in the realm of real estate.

## Created by:
- Siddhant Singh
- [@siddhant1601](https://github.com/siddhant1601)
