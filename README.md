# Customer Churn Analysis
## Project Overview

This project focuses on analyzing customer churn data to identify
patterns, trends and factors associated with customer attrition.

The analysis was performed using Python, SQL and SQLite with
data processing and visualization techniques.

## Tools & Technologies

- Python
- Pandas
- NumPy
- SQL
- SQLite
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Files

- Churn_analysis.ipynb – Complete analysis and visualizations
- Exported_churn_data.csv – Dataset used for analysis
- customer_churn.db – SQLite database
- Test_database.sqlite – Supporting database 

## Analysis Performed

- Data extraction
- Data cleaning and preprocessing
- SQL queries
- Exploratory Data Analysis (EDA)
- Feature engineering
- Customer churn analysis
- Data visualization
- Business insights

## Key Insights

Basic plan has the highest churn rate (~59%), compared with Standard (~19%) and Premium (~11%).
This indicates that customers on the Basic plan are significantly more likely to churn.

Premium customers show the lowest churn (~11%), suggesting comparatively stronger customer retention among premium-plan users.
Monthly churn is generally low but inconsistent.

Churned customers were around 1 in Feb, May, Oct and Nov, while September had the highest churn with 2 customers.
The September spike suggests a temporary increase in customer cancellations, although the overall number of churned customers is small.

The analysis indicates that plan type is an important factor associated with customer churn, with Basic-plan customers being the main churn-risk segment.

🔢 Pivot Table Analysis
Pivot tables were used to summarize the dataset and compare churn across different customer segments.
The analysis included comparisons based on relevant categorical and numerical variables to identify differences between churned and retained customers.
Pivot tables provided a quick way to aggregate and compare customer behavior across multiple dimensions.

Pairplot
A Pairplot was used to examine relationships between multiple numerical variables and understand how these variables differ across churn categories.

FaceGrid
FaceGrid was used to compare distributions and relationships across different customer segments, allowing patterns to be viewed across multiple categories simultaneously.
These techniques provided a deeper view of relationships that may not be visible through individual charts.
The analysis was performed to identify the major factors associated with customer churn.

Key findings includes:

Churn distribution was analyzed to understand the proportion of customers who left versus those who remained.
Customer churn was compared across different contract types.
Tenure was analyzed to understand its relationship with customer retention.
Monthly charges were compared between churned and retained customers.
Payment methods and service-related characteristics were examined for differences in churn behavior.
SQL queries and pivot tables were used to validate and summarize important patterns.
Pairplot and FacetGrid analysis were used to explore relationships between multiple variables.

## Author
Sanya Wadhwa
