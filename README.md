# NAIC-assignments
1. Sales Data Analysis using Python (NAICassignment1.ipynb)
Project Description
This project focuses on performing exploratory data analysis on a sales dataset. The goal is to understand business performance by identifying sales trends, customer behaviors, and product-level insights. Using Python libraries like pandas, matplotlib, and seaborn, the project delivers visual and statistical insights for better business decision-making.

Steps Covered
Data Loading

Loaded the dataset using pandas.

Displayed the first few rows to get an overview of the data structure.

Data Cleaning

Checked for missing values and handled them.

Renamed columns for consistency.

Converted data types where necessary, especially date columns.

Exploratory Data Analysis

Analyzed sales trends over time using line plots.

Identified top-performing products by grouping and aggregating data.

Visualized monthly sales, customer segments, and product categories using bar plots and pie charts.

Conducted geographic analysis if region or country data was present.

Insights

Derived insights such as peak sales months, most profitable products, and customer purchase behavior.

Recommended strategies to boost sales based on trends.

2. Churn Prediction Using Machine Learning (NAICassignment2.ipynb)
Project Description
This project involves predicting customer churn using machine learning algorithms. The objective is to identify customers who are likely to stop using a service so that targeted retention strategies can be implemented. The project involves preprocessing, training models, evaluating performance, and interpreting results.

Steps Covered
Data Loading and Inspection

Imported the dataset and inspected structure and types.

Checked class distribution for churn versus non-churn.

Data Preprocessing

Handled missing values.

Performed encoding of categorical variables using label encoding or one-hot encoding.

Scaled numerical features using standard scaler or min-max scaler.

Feature Selection

Identified important features using correlation analysis and domain knowledge.

Dropped irrelevant or redundant features.

Model Building

Split the data into train and test sets.

Trained different models including logistic regression, decision tree, and random forest.

Used accuracy, precision, recall, and F1-score to evaluate performance.

Model Tuning

Tuned hyperparameters using GridSearchCV or RandomizedSearchCV.

Selected the best-performing model.

Prediction and Output

Predicted churn for the test set.

Saved the model and predictions for future use.

Business Recommendation

Suggested customer retention actions based on churn likelihood.

Prioritized high-risk customers for proactive engagement.

3. Sales Dashboard using Power BI (NAICassignment3Dashboard.pbix)
Project Description
This project presents an interactive sales dashboard built using Power BI. The dashboard helps stakeholders monitor business performance by visualizing key performance indicators like total sales, profit, order quantity, and customer segments. It enables data-driven decision-making through intuitive visuals and filters.

Steps Covered
Data Import

Imported the sales dataset into Power BI from Excel.

Inspected the dataset and formatted columns such as date and numeric fields.

Data Modeling

Built relationships between tables if multiple datasets were used.

Ensured star schema or simple flat model depending on the structure.

DAX Measures Creation

Created custom measures such as Total Sales, Total Profit, Profit Margin, and Order Count using DAX.

Used calculated columns for fields like Year, Month, and Sales Category.

Visualizations

Created charts like line charts for trends, bar charts for category analysis, and pie/donut charts for proportions.

Used cards to show KPIs like total revenue and orders.

Included filters and slicers for region, product category, and date.

Interactive Features

Enabled drill-through functionality for detailed views.

Designed tooltip pages and bookmark navigation for storytelling.

Ensured responsive design for all visuals.

Insights and Narration

Highlighted top-selling products and profitable regions.

Added narrative panels or text boxes explaining trends and performance drivers.
