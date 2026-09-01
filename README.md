🏡 Ames Housing Price Analysis

📌 Project Overview

This project analyzes the Ames Housing Dataset to explore the factors associated with residential property sale prices.

The workflow covers data cleaning, feature engineering, exploratory data analysis (EDA), data visualization, outlier investigation, and SQL querying using Python and SQLite.

---

🛠️ Tools & Technologies

- Language: Python 3.x
- Data Manipulation: Pandas, NumPy
- Data Visualization: Matplotlib
- Database & Querying: SQLite3, SQL
- Environment: Jupyter Notebook, Git & GitHub

---

🔄 Project Workflow

1. Data Loading & Initial Inspection

The dataset was loaded using Pandas to examine its structure, data types, missing values, distributions, and basic summary statistics.

2. Data Cleaning

- Handled missing values based on the meaning of each variable, including categorical missing values that represent the absence of a feature.
- Checked for duplicate records and data inconsistencies.
- Investigated invalid and unusual values, including inconsistencies between construction and sale years.

3. Feature Engineering

Several features were created to support the analysis:

- "House_age": Property age at the time of sale.
- "Price_Per_Sq_Ft": Sale price divided by above-ground living area.
- "Overall_Qual_Num": Numeric representation of overall quality.
- "Luxury_House": Indicator for properties with an overall quality score of 8 or higher.
- "Price_Category": Categorical price segments defined for the analysis.
- "Total_Bathrooms": Combined metric of full and half bathrooms.
- "Is_Renovated": Indicates whether a property was remodeled after its original construction.

---

📊 Exploratory Data Analysis & Visualizations

The analysis explored relationships between property characteristics and sale prices.

1. Living Area vs Sale Price

Examining the relationship between above-ground living area and sale price:

"Living Area vs Price" (images/living_area_vs_price.png)

2. Overall Quality vs Sale Price

Exploring the relationship between overall quality and property sale price:

"Quality vs Price" (images/quality_vs_price.png)

3. Average Sale Price Trend by Year

Examining changes in average sale prices across the recorded sale years:

"Price by Year" (images/avg_price_by_year.png)

4. Room Count Impact on Sale Price

Exploring the relationship between above-ground room count and sale price:

"Price by Rooms" (images/price_by_rooms.png)

---

🔍 Outlier & Inconsistency Analysis

- Investigated unusually high and low "Price_Per_Sq_Ft" values.
- Examined records with unusual relationships between construction and sale years.
- Used related property characteristics to determine whether unusual observations represented potential data issues or valid cases.

---

🗄️ SQL Analysis

The cleaned dataset was loaded into a local SQLite database and analyzed using SQL queries to answer questions such as:

- Which neighborhoods have the highest average sale prices?
- Which properties have the highest sale prices?
- Which high-quality properties have relatively lower sale prices?

---

💡 Key Insights

- Overall Quality: Higher-quality properties tend to have higher sale prices.
- Living Area: Larger above-ground living areas are generally associated with higher sale prices.
- Neighborhood: Average sale prices vary considerably across neighborhoods.
- Room Count: Sale price generally increases with room count, although the relationship becomes less consistent at higher room counts.

---

🎯 Conclusion

This project demonstrates a practical data analysis workflow, from data inspection and cleaning to feature engineering, visualization, outlier investigation, and SQL querying.

The focus is on exploring the dataset and extracting meaningful insights about residential property prices.

---

👤 Author

Zahra Ahmadi

- GitHub: "zahraahmadi9700" (https://github.com/zahraahmadi9700)