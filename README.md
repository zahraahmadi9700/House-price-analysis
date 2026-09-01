🏡 Ames Housing Price Analysis

📌 Project Overview

This project analyzes the Ames Housing Dataset to explore the factors associated with residential property sale prices.

The analysis follows an end-to-end data analysis workflow, including data inspection, data cleaning, feature engineering, exploratory data analysis (EDA), data visualization, outlier investigation, and SQL analysis using Python and SQLite.

---

🛠️ Tools & Technologies

- Programming Language: Python
- Data Manipulation: Pandas, NumPy
- Data Visualization: Matplotlib
- Database & Querying: SQLite, SQL
- Environment: Jupyter Notebook
- Version Control: Git & GitHub

---

🔄 Project Workflow

1. Data Loading & Initial Inspection

The dataset was loaded using Pandas and examined to understand its structure, data types, missing values, distributions, and basic statistics.

2. Data Cleaning

The dataset was systematically checked for:

- Missing values
- Duplicate records
- Invalid values
- Inconsistent data
- Impossible relationships between construction and sale years

Missing values were handled based on the meaning of each variable. For example, missing categorical values indicating the absence of a feature were replaced with ""None"".

Potentially invalid or unusual observations were investigated before deciding how they should be handled.

3. Feature Engineering

Several domain-specific features were created to support further analysis:

- "House_age" — age of the house at the time of sale
- "Price_Per_Sq_Ft" — sale price divided by above-ground living area
- "Overall_Qual_Num" — numerical representation of overall quality
- "Luxury_House" — identifies properties with an overall quality score of 8 or higher
- "Price_Category" — groups properties into defined price segments
- "Total_Bathrooms" — combines full and half bathrooms into a single metric
- "Is_Renovated" — identifies properties remodeled after their original construction

4. Exploratory Data Analysis

The analysis explored relationships between property characteristics and sale prices, including:

- Living area and sale price
- Overall quality and sale price
- House age and sale price
- Number of rooms and sale price
- Average sale price by year
- Average sale price by neighborhood
- Price per square foot across neighborhoods

Visualizations were used to identify patterns, relationships, and unusual observations in the data.

5. Outlier & Inconsistency Analysis

Unusual observations were investigated rather than being automatically removed.

The analysis focused particularly on:

- Extremely high or low price-per-square-foot values
- Unusual property characteristics
- Records where the sale year was earlier than the construction year

These observations were examined in context to distinguish potentially valid cases from actual data quality issues.

6. SQL Analysis

The cleaned dataset was loaded into a SQLite database and analyzed using SQL queries.

The SQL analysis addressed questions such as:

- Which neighborhoods have the highest average sale prices?
- Which properties have the highest sale prices?
- Which lower-priced properties have relatively high overall quality?

This section demonstrates the use of SQL alongside Pandas for structured data analysis.

---

💡 Key Findings

- Overall quality has a strong positive relationship with sale price.
- Larger living areas are generally associated with higher sale prices.
- House age shows a negative relationship with sale price, although this relationship is not absolute.
- Neighborhood has a substantial impact on average sale prices, indicating differences in location value.
- Room count generally has a positive relationship with price, although the relationship becomes less consistent for properties with a very large number of rooms.
- Some properties have unusual characteristics that require investigation rather than being automatically treated as errors.

---

🎯 Conclusion

This project demonstrates a complete data analysis workflow using Python, Pandas, NumPy, Matplotlib, and SQL.

It covers the process from raw data inspection and