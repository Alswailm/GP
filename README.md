# Comparative Analysis of Machine Learning Models for Villa Price Prediction in Riyadh, Saudi Arabia

## Reproducibility

This document outlines the steps necessary to reproduce the results of the villa price prediction study using the 'Riyadh Villas - Aqar' dataset.

## Methodology

### Experimental Design
The experimental design involved selecting and comparing several regression models to predict villa prices in Riyadh. The models included Simple Linear Regression (SLR), Random Forest (RF), and XGBoost. The process consisted of the following steps:

1. **Feature Processing:** Categorical features like ‘front’, ‘location’, and ‘neighbourhood’ were converted to numerical format using Label Encoding.
2. **Data Splitting:** The dataset was split into training (80%) and test (20%) sets to train the models and evaluate their performance.
3. **Data Processing:** The data was processed using Python libraries such as Pandas for data manipulation and Scikit-learn for model training and evaluation. Key steps included:
   - **Feature Encoding:** Categorical variables were encoded using Label Encoder.
   - **Model Training:** Models were trained on the training set and evaluated using the test set.

## Code

### Source code
The source code used in this study is available on GitHub. You can access it through the following link: [SourceCode](https://github.com/Alswailm/GP/blob/main/Graduadion%20Project.ipynb).

## Data Availability

### Data Sources
The data used in this research was sourced from Kaggle. You can access the dataset here: [Riyadh Villas - Aqar](https://www.kaggle.com/datasets/reemamuhammed/riyadh-villas-aqar).

### Data Description
The dataset contains features relevant to villa pricing, including:
- **Location:** Categorical variable representing the location of the villa.
- **Neighbourhood:** Categorical variable representing the neighbourhood of the villa.
- **Space:** Numerical variable representing the size of the villa.
- **Price:** Target variable representing the price of the villa.

## Replication Instructions

### Steps to Reproduce
1. **Set Up Environment:** Install necessary Python packages (e.g., Pandas, Scikit-learn).
2. **Download Dataset:** Retrieve the dataset from Kaggle using the provided link.
3. **Run Code:** Execute the scripts from the GitHub repository to replicate the results.
4. **Evaluate Models:** Use the provided scripts to train and evaluate the models using the same metrics (MAPE and R-Squared).

## Computing Infrastructure

- **Operating System:** Windows 10 Pro, Version 21H1
- **Hardware:**
  - **CPU:** Intel Core i7-10700K
  - **RAM:** 16 GB DDR4
  - **GPU:** NVIDIA GeForce RTX 3080 (if applicable)
  - **Storage:** 1 TB SSD

