# Fake News Detection using Machine Learning

This project demonstrates the application of machine learning models to classify news articles as real or fake. The project uses the WELFake Dataset, a labeled dataset containing text data and corresponding labels.

## Overview

The notebook performs the following steps:

1. **Data Loading and Preprocessing**:
   - The dataset is loaded using pandas.
   - Missing values in the 'text' column are dropped.
   - The data is split into features (text data) and labels (real/fake).
   - The dataset is then split into training and testing sets using an 80/20 split.

2. **Text Vectorization**:
   - The text data is transformed using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert the textual data into numerical features suitable for machine learning models.

3. **Model Training and Evaluation**:
   - Three different machine learning models are trained on the TF-IDF transformed data:
     - **Multinomial Naive Bayes**
     - **Logistic Regression**
     - **Decision Tree Classifier**
   - Each model is evaluated on the test set, and classification reports are generated to show the precision, recall, f1-score, and accuracy of the models.

## Requirements

The following Python libraries are used in this project:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`

You can install the required libraries using:
```bash
pip install numpy pandas scikit-learn matplotlib
```
**Problem**

A leading global leader of e-commerce has over 150 million paid subscription users. One of the many perks of the subscription is the privilege of buying products at lower prices. For an upcoming sale, the organization has decided to promote local artisans and their products, to help them through these tough times. However, slashed prices may impact local artists.
To not let discounts affect local artists, the company has decided to determine the lowest price at which a particular good can be sold. Your task is to build a predictive model using Machine Learning that helps them set up a lowest-pricing model for these products.
You have to predict the Low_Cap_Price column.

**Q1.Describe the problem in your own words?**

Ans: This code builds a machine learning model using linear regression to predict the lowest price at which products can be sold during a sale event on an e-commerce platform. The model considers various factors such as date, market category, product category, grade, and demand to make accurate predictions. The goal is to ensure that local artisans are not negatively impacted by discounts while promoting their products. The model's performance is evaluated using root mean squared error (RMSE) as an accuracy measure.

**Q2.Explain how linear regression can help solve this problem?**

Ans: Linear regression can help solve this problem by finding a linear relationship between the input features (such as date, market category, product category, grade, and demand) and the target variable (lowest price). By training the model on historical data, it learns the coefficients that represent the impact of each feature on the lowest price. This allows the model to predict the lowest price for new instances based on their feature values, helping the e-commerce platform set appropriate pricing for products during sales events while considering the impact on local artisans.
