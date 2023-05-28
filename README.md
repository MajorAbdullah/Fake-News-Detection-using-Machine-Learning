# AI_Machine_Learning

**Problem**

A leading global leader of e-commerce has over 150 million paid subscription users. One of the many perks of the subscription is the privilege of buying products at lower prices. For an upcoming sale, the organization has decided to promote local artisans and their products, to help them through these tough times. However, slashed prices may impact local artists.
To not let discounts affect local artists, the company has decided to determine the lowest price at which a particular good can be sold. Your task is to build a predictive model using Machine Learning that helps them set up a lowest-pricing model for these products.
You have to predict the Low_Cap_Price column.

**Q1.Describe the problem in your own words?**

Ans: This code builds a machine learning model using linear regression to predict the lowest price at which products can be sold during a sale event on an e-commerce platform. The model considers various factors such as date, market category, product category, grade, and demand to make accurate predictions. The goal is to ensure that local artisans are not negatively impacted by discounts while promoting their products. The model's performance is evaluated using root mean squared error (RMSE) as an accuracy measure.

**Q2.Explain how linear regression can help solve this problem?**

Ans: Linear regression can help solve this problem by finding a linear relationship between the input features (such as date, market category, product category, grade, and demand) and the target variable (lowest price). By training the model on historical data, it learns the coefficients that represent the impact of each feature on the lowest price. This allows the model to predict the lowest price for new instances based on their feature values, helping the e-commerce platform set appropriate pricing for products during sales events while considering the impact on local artisans.
