# Kidney Stone Prediction
<div align="center">
<img src="https://domf5oio6qrcr.cloudfront.net/medialibrary/9795/GettyImages-843352558.jpg" width="600">
</div>

## About dataset
The kidney-stone-dataset.csv is a comma-separated values file containing data on patients with kidney stones. The file has 90 rows and 8 columns, with each row representing a patient and each column providing information on various characteristics and laboratory test results. The dataset includes a target variable, "target", which is a continuous variable representing the risk of developing kidney stones. The dataset can be used for tasks such as predicting the risk of kidney stones based on patient characteristics and test results.

The eight columns in the dataset are as follows:

- gravity: the specific gravity of urine
- pH: the pH level of urine
- osmo: the osmolarity of urine
- cond: the conductivity of urine
- urea: the urea concentration of urine
- calc: the calcium concentration of urine
- target: the risk of developing kidney stones (continuous variable)
- shape: the shape of the dataset (90, 8)

## Performing Basic EDA and training
To explore the dataset, I have performed basic EDA by loading the dataset into Python's Pandas library. I have checked for missing values, computed summary statistics, and created visualizations of the data. This EDA helps in understanding the dataset and identifying potential issues that need to be addressed before training models.

This project aims to predict the risk of developing kidney stones based on patient characteristics and test results. The dataset used for this project contains various features related to kidney stones, such as age, gender, and various medical test results.

Several machine learning algorithms were used to train, test and evaluate the model, including:

- Logistic Regression
- Decision Tree
- Random Forest
- SVM
- Gradient Boosting
- Artificial Neural Networks 

## Conclusion :

This project demonstrates the effectiveness of machine learning algorithms for predicting the risk of developing kidney stones. The results suggest that the Decision Tree algorithm can be a valuable tool for healthcare professionals in developing prevention and treatment strategies for kidney stones. Also the data available was too less to train any powerful ML, DL algorithms.
