Black Friday Sales Analysis
By Ganesh Dhanishetty

Overview
This project provides a comprehensive exploratory data analysis (EDA) of the Black Friday sales dataset. The goal is to uncover insights about sales trends, customer demographics, and product performance using various statistical and visualization techniques.

Dataset
The dataset used in this analysis is the Black Friday Sales Dataset, which contains transaction data, including:

Customer details (age, gender, occupation, marital status, etc.)
Product information
Purchase amounts
File Structure
BlackFriday.csv: The dataset file.
black_friday_sales_analysis.ipynb: Jupyter Notebook containing the EDA code.
README.md: This documentation file.

Analysis Steps
1. Importing Required Libraries
Libraries used: pandas, seaborn, numpy, matplotlib.

3. Loading the Dataset
Load the dataset into a pandas DataFrame for analysis.

5. Initial Data Exploration
Display the first five rows of the dataset (head() method).
Use info() to understand data types and missing values.
Display unique value counts for each column.
Use describe() for statistical summaries.

7. Handling Missing Values
Identify columns with missing values.
Drop columns with a significant percentage of missing data.

9. Detailed Column Analysis
Analyze customer demographics, product categories, and purchase behavior:
Unique users and products.
Gender distribution.
Age ranges and occupations.
City categories and stay durations.
Marital status distribution.
Product category performance.
Calculate mean purchase values.

11. Univariate Analysis
Visualize individual variables using:
Gender Ratio: Bar and pie charts.
City Categories: Pie charts.
Purchase Amounts: Box plots.
Marital Status: Pie charts.
Occupation and Stay Duration: Bar charts.

13. Bivariate Analysis
Explore relationships between variables with visualizations:
Purchases by Age: Bar charts.
Products Purchased by Age: Bar charts.
Purchase Distribution by Gender: Pie charts.
Top 10 Product IDs: Bar charts.

15. Multicolumn Analysis
Analyze combinations of demographic factors using count plots:
Age vs. Gender
Gender vs. Marital Status
City Category vs. Age
Marital Status vs. City Category
City Category vs. Gender
Stay Duration vs. Gender
Stay Duration vs. Marital Status

17. Combining Gender and Marital Status
Create a new column combining gender and marital status.
Analyze this column against other demographic factors (e.g., city category, age).

Conclusion
This analysis highlights key insights into Black Friday sales data:
Customer Demographics: Age, gender, marital status, and occupation trends.
Purchase Behavior: Spending patterns across genders and age groups.
Product Performance: Identification of top-performing products.
