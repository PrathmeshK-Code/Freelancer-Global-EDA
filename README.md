# Freelancer-Global-EDA
This repository contains an Exploratory Data Analysis (EDA) project focused on a dataset of global freelancers. The analysis aims to segment freelancers based on various attributes for targeted strategies.

File Description:
- Untitled1.ipynb: Jupyter Notebook with Python code for:
- Loading and inspecting the global_freelancers_raw.csv dataset.
- Cleaning data (e.g., gender, hourly rate, client satisfaction, is_active, rating).
- Performing EDA with statistical summaries and visualizations.
- Applying KMeans clustering and PCA for segmentation into performance clusters.

Data Cleaning:
- Standardized gender, hourly_rate (USD), client_satisfaction, is_active, and rating columns.
- Handled missing values with mean imputation for numerical data and categorical imputation for gender.
- Dropped original uncleaned columns to create df_cleaned.

Analysis:
- Exploratory Data Analysis: Generated descriptive statistics and scatter plots using PCA to visualize performance clusters.
- Clustering: Used KMeans to segment freelancers based on features like experience, hourly rate, rating, and satisfaction.
- Visualizations: Included plots to identify clusters with low ratings and satisfaction for performance improvement.
