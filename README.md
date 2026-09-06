Customer Churn Analysis

Project Overview

This project focuses on analyzing customer churn data to understand customer behavior, identify patterns associated with churn, and generate meaningful business insights.

The project follows an end-to-end data analysis workflow using Python, SQL and SQLite, covering data preparation, exploratory analysis, SQL-based analysis, pivot tables and data visualization.

⸻

Business Problem

Customer churn can have a significant impact on business revenue and customer retention.

The objective of this project is to analyze customer data and answer questions such as:

* How many customers have churned?
* Which customer segments have higher churn?
* Does contract type affect customer churn?
* How do tenure and monthly charges relate to churn?
* Which services or customer characteristics are associated with higher churn?
* What patterns can be identified from the data using SQL and Python?

Tools & Technologies

* Python
* Pandas – Data manipulation and analysis
* NumPy – Numerical operations
* Matplotlib – Data visualization
* Seaborn – Statistical visualization
* SQL – Data querying and analysis
* SQLite – Database management
* Jupyter Notebook – Development and analysis environment

📂 Project Files

File	Description
Churn_analysis.ipynb	Complete Python, SQL and exploratory data analysis
Exported_churn_data.csv	Dataset used for analysis
customer_churn.db	SQLite database used for SQL analysis
Test_database.sqlite	Supporting SQLite database, if required

🔄 Project Workflow

The project follows these major stages:

Data Collection → Data Cleaning → Data Transformation → SQL Analysis → Exploratory Data Analysis → Pivot Table Analysis → Visualization → Business Insights

Data Cleaning & Preprocessing

The dataset was examined and prepared before analysis.

Key steps included:

* Inspecting the dataset structure
* Checking data types
* Identifying missing values
* Checking duplicate records
* Handling data inconsistencies
* Converting variables into appropriate formats
* Preparing the dataset for SQL and exploratory analysis

🗄️ SQL Analysis

The customer data was stored and analyzed using SQLite.

SQL queries were used to:

* Filter customer records
* Group customers based on different attributes
* Calculate customer counts
* Compare churn across different segments
* Aggregate customer-related metrics
* Identify patterns in customer churn

This helped perform structured analysis directly from the database.

🔢 Pivot Table Analysis

Pivot tables were used to summarize the dataset and compare churn across different customer segments.

The analysis included comparisons based on relevant categorical and numerical variables to identify differences between churned and retained customers.

Pivot tables provided a quick way to aggregate and compare customer behavior across multiple dimensions.

📊 Exploratory Data Analysis

Exploratory Data Analysis was performed using Pandas, Matplotlib and Seaborn.

The analysis explored relationships between churn and variables such as:

* Contract type
* Tenure
* Monthly charges
* Payment method
* Internet/service-related variables
* Customer demographics
* Other relevant customer attributes

📈 Data Visualization

Multiple visualization techniques were used to understand patterns in the dataset.

Visualizations included:

* Bar charts
* Count plots
* Histograms
* Distribution plots
* Box plots
* Pair plots
* FacetGrid visualizations
* Comparative plots

These visualizations helped identify differences and relationships between customer characteristics and churn behavior.

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
