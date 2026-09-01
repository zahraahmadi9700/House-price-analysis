🏡 Ames Housing Price Analysis

📌 Overview

This project analyzes the Ames Housing Dataset to explore the factors associated with residential property sale prices.

The analysis covers data cleaning, exploratory data analysis (EDA), feature engineering, data visualization, outlier investigation, and SQL analysis using Python and SQLite.

🛠️ Tools & Technologies

- Python
- Pandas & NumPy
- Matplotlib
- SQLite & SQL
- Jupyter Notebook

🔄 Analysis Workflow

🧹 Data Cleaning

- Inspected data types, missing values, and duplicates
- Checked for invalid and inconsistent values
- Handled missing values based on the meaning of each variable
- Investigated unusual observations before making changes

🔧 Feature Engineering

Created several features to support the analysis:

- "House_age"
- "Price_Per_Sq_Ft"
- "Overall_Qual_Num"
- "Total_Bathrooms"
- "Price_Category"
- "Luxury_House"
- "Is_Renovated"

📊 Exploratory Data Analysis

The analysis examines relationships between sale price and important property characteristics.

1. Living Area vs Sale Price

"Living Area vs Price" (images/living_area_vs_price.png)

2. Overall Quality vs Sale Price

"Quality vs Price" (images/quality_vs_price.png)

3. Average Sale Price Trend by Year

"Price by Year" (images/avg_price_by_year.png)

4. Room Count Impact on Sale Price

"Price by Rooms" (images/price_by_rooms.png)

🔎 Outlier & Anomaly Investigation

Potentially unusual observations were investigated using related variables rather than being automatically removed.

The analysis included unusual price-per-square-foot values and inconsistent relationships between construction and sale years.

🗄️ SQL Analysis

The cleaned dataset was loaded into SQLite and analyzed using SQL queries to explore:

- Average sale prices by neighborhood
- Highest-priced properties
- High-quality properties with relatively lower prices

💡 Key Insights

- Overall quality has a strong positive relationship with sale price.
- Living area is generally positively associated with sale price.
- Neighborhood plays an important role in differences in property prices.
- House age tends to have a negative relationship with sale price.
- Price per square foot provides an additional perspective for comparing properties of different sizes.

🎯 Conclusion

This project demonstrates a practical data analysis workflow, from inspecting and cleaning raw data to feature engineering, visualization, anomaly investigation, and SQL querying.

The focus is on understanding the data and extracting meaningful insights, rather than building a machine learning model.

👤 Author

Zahra Ahmadi

"GitHub" (https://github.com/zahraahmadi9700)