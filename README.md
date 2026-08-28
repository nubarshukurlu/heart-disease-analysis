# Heart Disease Data Analysis
## About the Project
This project explores a heart disease dataset containing patient information from different regions.

The analysis focuses on understanding the data, identifying regional differences, handling missing and unrealistic values,
building a predictive model, and exploring patient groups using clustering techniques.

The project combines exploratory data analysis, data preprocessing, supervised learning, and unsupervised learning.

## Main Goals

The main goals of this project are:

- Explore the structure and quality of the heart disease dataset
- Compare patient characteristics across different regions
- Identify and handle missing or unrealistic values
- Investigate factors associated with heart disease
- Build and evaluate a Logistic Regression model
- Examine whether model behavior is consistent across regions
- Discover patient subgroups using K-Means clustering
- Interpret differences between the identified groups

## Analysis Workflow

### 1. Data Exploration

- Dataset structure and variable types
- Numerical and categorical feature identification
- Missing value analysis
- Distribution analysis
- Correlation analysis

### 2. Regional Analysis

- Comparison of patient populations
- Heart disease prevalence across regions
- Comparison of important clinical variables
- Investigation of regional patterns

### 3. Data Preparation

- Detection of missing values
- Identification of unrealistic clinical values
- Replacement of invalid zero values
- Missing value imputation
- Creation of a cleaned dataset

### 4. Predictive Modeling

A Logistic Regression model was used as the baseline classification model.

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC

### 5. Regional Stability

The analysis also investigates whether relationships between patient characteristics and heart disease remain consistent across different regions.

### 6. Patient Segmentation

K-Means clustering was used to explore hidden structures in the patient data.

The clustering analysis includes:

- Feature scaling
- Elbow Method
- Silhouette Score
- Selection of the number of clusters
- Comparison of patient characteristics across clusters
- Interpretation of identified patient groups


## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook


## Repository Contents

```text
heart-disease-analysis/
│
├── data/
│   ├── heart.csv
│   └── heart_cleaned.csv
│
├── Notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_population_comparison.ipynb
│   ├── 03_data_cleaning.ipynb
│   ├── 04_modeling.ipynb
│   ├── 05_stability_across_regions.ipynb
│   ├── 06_unknown_structure.ipynb
│   └── 07_interpreting_differences.ipynb
│
└── README.md
