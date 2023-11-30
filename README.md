# Industrial Copper Modeling Project

## Project Description

The Industrial Copper Modeling project aims to address challenges in the copper industry related to sales prediction and lead classification. It involves the development of machine learning models for predicting selling prices and classifying leads as either successful (WON) or unsuccessful (LOST). The project also includes the creation of a Streamlit web application for interactive predictions.

## Skills Developed

- Python scripting
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Machine learning regression and classification
- Streamlit web application development

## Domain

Manufacturing

## Problem Statement

The copper industry deals with less complex data related to sales and pricing. However, this data may suffer from issues such as skewness and noisy data, which can affect the accuracy of manual predictions. A machine learning regression model can address these issues by utilizing advanced techniques such as data normalization, feature scaling, and outlier detection, and leveraging algorithms that are robust to skewed and noisy data.

Another area where the copper industry faces challenges is in capturing the leads. A lead classification model is a system for evaluating and classifying leads based on how likely they are to become a customer. You can use the STATUS variable with WON being considered as Success and LOST being considered as Failure and remove data points other than WON, LOST STATUS values.

## Solution Steps

1. **Data Understanding**: Identify the types of variables (continuous, categorical) and their distributions. Treat reference columns as categorical variables. INDEX may not be useful.

2. **Data Preprocessing**:
   - Handle missing values with mean/median/mode.
   - Treat outliers using IQR or Isolation Forest from sklearn library.
   - Identify Skewness in the dataset and treat skewness with appropriate data transformations.
   - Encode categorical variables using suitable techniques.

3. **EDA**:
   - Visualize outliers and skewness using Seaborn’s boxplot, distplot, violinplot.
   
4. **Feature Engineering**:
   - Engineer new features if applicable.
   - Drop highly correlated columns.

5. **Model Building and Evaluation**:
   - Split the dataset into training and testing sets.
   - Train and evaluate different classification models (e.g., ExtraTreesClassifier, XGBClassifier, Logistic Regression) using appropriate evaluation metrics.
   - Optimize model hyperparameters using techniques such as cross-validation and grid search.

6. **Model GUI (Streamlit)**:
   - Create an interactive page where users can input values for prediction.
   - Perform the same feature engineering, scaling, and transformation steps used for training the models.
   - Display the predicted output.

## Learning Outcomes

This project will help you develop proficiency in:

- Python programming language and its data analysis libraries.
- Data preprocessing techniques such as handling missing values, outlier detection, and data normalization.
- Understanding and visualizing data using EDA techniques.
- Applying advanced machine learning techniques for regression and classification tasks.
- Building and optimizing machine learning models using appropriate evaluation metrics and techniques.
- Feature engineering to create informative representations of the data.
- Developing web applications using the Streamlit module.

## Additional Notes

- Use the `pickle` module to save and load models, encoders, scalers, etc.
- Fit and then transform data separately for unseen data.

## Conclusion

This project equips you with practical skills and experience in data analysis, machine learning modeling, and creating interactive web applications. It provides a solid foundation to tackle real-world problems in the manufacturing domain.

---

*Note: Provide appropriate file paths and directory structures in the project's code and documentation.*
