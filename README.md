# Comparison-of-the-Classical-Linear-Regression-and-Artificial-Neural-Network-Models
This project compares the performance of the Classical Linear Regression (CLM) model and the Artificial Neural Network (ANN) model for predicting and classifying cancer data. Specifically, the dataset used is the Breast Cancer Wisconsin (Diagnostic) dataset.
## Objective
The goal of this study is to compare the effectiveness of Classical Linear Regression and Artificial Neural Networks in predicting cancer data. The evaluation metrics used to compare the models are:

- Coefficient of Determination (R²)
- Root Mean Squared Error (RMSE)
## Key Findings
The Classical Linear Model (CLM) showed a slightly higher RMSE compared to the Perceptron Model (PM). The RMSE difference between CLM and PM was approximately 0.000175071.
Despite the small difference in RMSE values, the Perceptron Model outperformed the Classical Linear Model in terms of predictive accuracy, with a lower RMSE value.
The Coefficient of Determination (R²) showed a slight edge for the Perceptron Model, being 0.04% better than the Classical Linear Model.
Based on the findings, the Perceptron Model is recommended as a better predictive model than the Classical Linear Model for this dataset.
Data Preprocessing and Model Building
The data was first cleaned by removing unwanted or missing values and converting categorical data into numerical format for machine learning model compatibility. Following the cleaning process, two models were built and evaluated:

- Classical Linear Model (CLM) using traditional linear regression.
- Perceptron Model (PM) using an Artificial Neural Network (ANN) approach.

## Steps Involved
1.  Data Cleaning: Handling missing values, encoding categorical variables, and normalizing numerical values.
2.  Model Building:
- Classical Linear Regression: Trained using sklearn.linear_model.LinearRegression.
- Artificial Neural Network (Perceptron): Built using tensorflow.keras.
3.  Model Evaluation: Using RMSE and R² to assess model performance.
4.  Comparison: The two models were compared based on the RMSE and R² values.
## Results
- The Perceptron Model showed superior predictive performance with a lower RMSE and a slightly higher R² value than the Classical Linear Model.
- The RMSE difference between the two models was 0.000175071, favoring the Perceptron Model.
## Conclusion
Based on the results from the Breast Cancer Wisconsin (Diagnostic) dataset, the Perceptron Model outperforms the Classical Linear Model in terms of prediction accuracy. Therefore, the study recommends the Perceptron Model as a better alternative for cancer prediction tasks in similar datasets.
