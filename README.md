Python Projects

A collection of beginner-to-intermediate level Python projects focused on data analysis and machine learning. 
This repository currently includes three Jupyter notebooks: EDA_netflix.ipynb, Classification.ipynb, and Regression.ipynb. 
Below is a detailed conceptual summary of each notebook, excluding code.

EDA_netflix.ipynb

Dataset

Netflix Titles Dataset (8,800+ entries, 12 features)
Objective

Explore and analyze the Netflix dataset to uncover insights about content genres, regional distribution, content types, and trends over time.
Tools & Technologies Used

Python : Pandas, NumPy, Matplotlib, Seaborn, Plotly (for interactive visualizations)
Process Overview

Data Loading: Netflix dataset is loaded and structure is inspected.
Data Cleaning:
Dropped irrelevant columns.
Renamed columns for clarity.
Handled missing values.
Exploratory Analysis:
Distribution of content ratings analyzed.
Most popular genres and genre combinations identified.
Prepared cleaned dataset for further visual analysis.
Questions Explored

What are the top genres on Netflix?
Which countries are most represented?
What is the split between Movies and TV Shows?
How has content addition changed over time?
Skills Demonstrated

Data inspection and cleaning
Handling missing data
Categorical analysis
Visual storytelling with interactive plots
Classification.ipynb

Dataset

Titanic Dataset : Used for binary classification to predict passenger survival
Objective

Build classification models to predict survival of passengers using engineered features.
Tools & Technologies Used

Python : Pandas, NumPy, Scikit-learn
Process Overview

Data Cleaning:
Dropped noisy and irrelevant columns.
Filled missing values.
Removed Cabin due to high null counts.
Feature Engineering:
Encoded categorical variables (Sex, Embarked).
Dropped PassengerId, Name, SibSp, Parch, Ticket.
Model Preparation:
Dataset prepared for Logistic Regression, SVM, Random Forest, and XGBoost.
Target variable: Survived
Skills Demonstrated

Data preprocessing for classification
Feature encoding
Dataset preparation for multiple ML models
Understanding classification workflows
Regression.ipynb

Dataset

Housing Dataset : Used for predicting continuous values (House Prices)
Objective

Build regression models to predict house prices using transformed and engineered features.
Tools & Technologies Used

Python : Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Process Overview

Feature Engineering:
Created new features
Dropped less relevant columns post-feature creation
EDA:
Correlation heatmaps and visualizations
Target Transformation:
Applied log transformation to house price
Model Preparation:
Features selected: Square Footage, Lot Size, Garage Size, Neighborhood Quality, Rooms, Years
Skills Demonstrated

Regression modeling setup
Target transformation (log-scale)
Visual EDA for numeric data
Feature construction and reduction
Summary

Each notebook reflects a key data science task:

EDA_netflix.ipynb: Exploratory data analysis and visualization
Classification.ipynb: Supervised learning – classification with the Titanic dataset
Regression.ipynb: Supervised learning – regression for house price prediction
This repository highlights strong foundational skills in:

Data cleaning & preprocessing
Feature engineering
Visualization and storytelling
Preparing datasets for machine learning models
