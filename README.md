# Chronic-Kidney-Disease-Classification
Developed a Chronic Kidney Disease classification model using a dataset of 400 patient records with 24 clinical features, achieving 98-100% accuracy with ensemble methods like Random Forest and Gradient Boosting. This project involved robust data preprocessing and feature engineering to handle missing values and categorical inconsistencies.


Project Description:

This project focuses on building a highly accurate machine learning model to classify patients with Chronic Kidney Disease (CKD) using clinical and laboratory parameters. Leveraging a dataset of 400 patient records and 24 features (11 numerical, 14 categorical), the workflow includes robust data preprocessing, exploratory analysis, and ensemble modeling to achieve 98-100% test accuracy.

Key Features:

Data Cleaning & Preprocessing:

Addressed 152 missing values in red_blood_cells and 106 missing values in white_blood_cell_count using random sampling and mode imputation.

Fixed inconsistencies in categorical features (e.g., \tno → no, ckd\t → ckd).

Converted mislabeled numerical/categorical columns (e.g., specific_gravity, albumin).

Exploratory Data Analysis:

Identified skewed distributions in critical features like blood_urea and serum_creatinine.

Visualized correlations (e.g., hemoglobin ↔ packed_cell_volume with 0.96 Pearson correlation).

Model Development:

Tested 10+ algorithms, including KNN, Decision Trees, Random Forest, AdaBoost, XGBoost, and LightGBM.

Achieved 100% test accuracy with tuned Random Forest, AdaBoost, and Gradient Boosting models.

Optimized hyperparameters using GridSearchCV (e.g., max_depth=7, criterion=entropy for Decision Trees).

Performance Highlights:

Best Model: Random Forest (criterion='entropy', max_depth=11) with 100% precision, recall, and F1-score.

Feature Importance: Key predictors included hemoglobin, blood_urea, and packed_cell_volume.

Technical Stack:

Tools: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, LightGBM, CatBoost.

Methods: Label Encoding, KDE Plots, Heatmaps, GridSearchCV, Ensemble Learning.
