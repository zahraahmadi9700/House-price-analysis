Ames House Price Analysis

Project Overview

This project analyzes the Ames Housing dataset to explore the factors associated with house sale prices.

The project focuses on data cleaning, feature engineering, exploratory data analysis (EDA), data visualization, and SQL analysis using Python.

Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- SQLite
- Jupyter Notebook

Project Workflow

1. Data Loading & Initial Inspection

The dataset was loaded using Pandas and examined to understand its structure, columns, data types, missing values, and basic statistics.

2. Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate records
- Invalid values
- Inconsistent data
- Impossible relationships between construction and sale years

Missing values were handled based on the meaning of each variable. For example, missing categorical values representing the absence of a feature were replaced with ""None"".

3. Feature Engineering

Several new features were created to make the dataset more useful for analysis:

- "House_age" — age of the house at the time of sale
- "Price_Per_Sq_Ft" — sale price divided by living area
- "Overall_Qual_Num" — numerical representation of overall quality
- "Luxury_House" — identifies houses with an overall quality score of 8 or higher
- "Price_Category" — groups houses into price ranges
- "Total_Bathrooms" — combines full and half bathrooms
- "Is_Renovated" — identifies houses where remodeling occurred after construction

4. Exploratory Data Analysis

The analysis examined relationships between house characteristics and sale prices, including:

- Living area and sale price
- Overall quality and sale price
- House age and sale price
- Number of rooms and sale price
- Average sale price by year
- Average sale price by neighborhood
- Price per square foot across neighborhoods

5. Outlier Analysis

Unusual observations were investigated, particularly properties with extremely high or low price per square foot.

The analysis also identified records where the sale year was earlier than the construction year and investigated these observations further.

6. SQL Analysis

The cleaned dataset was loaded into a SQLite database and analyzed using SQL queries.

The SQL analysis included:

- Top neighborhoods by average sale price
- Most expensive properties
- Lower-priced properties with high overall quality

Key Findings

- Overall quality has a strong positive relationship with sale price.
- Larger living areas are generally associated with higher sale prices.
- Older houses tend to have lower sale prices, although this relationship is not absolute.
- Average sale prices vary substantially between neighborhoods.
- Average sale price generally increases as the number of rooms increases, although the relationship becomes less consistent for houses with very large numbers of rooms.
- The dataset contains unusual observations that require further investigation rather than being automatically treated as errors.

Conclusion

This project demonstrates a complete data analysis workflow using Python, Pandas, NumPy, Matplotlib, and SQL. It covers the process from raw data inspection and cleaning to feature engineering, exploratory analysis, visualization, outlier investigation, and database querying.

## Author 
Zahra Ahmadi