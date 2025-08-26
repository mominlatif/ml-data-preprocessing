📊 ML Data Preprocessing: Data Cleaning & Feature Engineering
📌 Overview

This project demonstrates data cleaning and feature engineering techniques on a real-world dataset. The objective is to prepare messy, inconsistent, or incomplete data into a format ready for machine learning modeling.

🎯 Objectives

Handle missing, inconsistent, and duplicate values

Fix incorrect data formats and types

Detect and treat outliers

Engineer meaningful new features

Encode categorical variables

Normalize/scale numerical features

Split dataset into train/test sets for ML

📂 Dataset

Source: [Kaggle / UCI Repository / Public Dataset of your choice]

Format: CSV

Description: [Brief description of the dataset — e.g., contains demographic, transaction, or survey data used for ML tasks.]

🛠 Steps Performed
🔹 Data Cleaning

Loaded dataset in Pandas

Handled missing values (drop / fill with mean/median/mode)

Removed duplicate records

Fixed inconsistent formats (case sensitivity, date formats, etc.)

Converted data types (object → datetime/int/float)

Detected & treated outliers (IQR/Z-score method)

🔹 Feature Engineering

Extracted useful information from date/time columns (year, month, weekday, etc.)

Created new features (e.g., age, ratios, differences between columns)

Encoded categorical features using Label Encoding & One-Hot Encoding

Scaled/normalized numerical features using StandardScaler / MinMaxScaler

(Optional) Applied PCA for dimensionality reduction

🔹 Dataset Splitting

Train-test split (80/20)

Stored cleaned dataset as cleaned_data.csv

📊 Visualizations

Distribution plots of features before/after cleaning

Heatmap of missing values

Boxplots & histograms for outlier detection
