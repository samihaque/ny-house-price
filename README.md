# NYC House Price Prediction
**Introduction:** The project, "Predict the House Price, NYC," aims to forecast the prices of houses in various neighborhoods of New York City (NYC). By utilizing data analysis and machine learning techniques in Python, we aim to uncover crucial factors and trends that influence house prices, ultimately aiding individuals in finding their ideal homes.

## **Objective:** 
The primary objective of this project is to develop an accurate predictive model for house prices in NYC. By analyzing a comprehensive dataset containing various features such as location, size, amenities, and other relevant factors, we intend to build a model that can effectively predict house prices. The ultimate goal is to provide valuable insights to both homebuyers and real estate stakeholders, facilitating informed decision-making processes.

## **Link to dataset:** [dataset](https://www.kaggle.com/datasets/nelgiriyewithana/new-york-housing-market/data)


## **Link to complete project details, description and analysis results:** [website](https://sites.google.com/view/find-out-nyc-house-price/home)

## **Machine Learning Model used:** 
Upon preprocessing the dataset, we proceeded to utilize four distinct machine learning algorithms for predictive analysis. Which are:
K-nearest Neighbor (KNN), Random Forest Regression, Gradient Boost Regression and CatBoost Regression.

## **Summary of Results:**
**Among the models, CatBoost Regression achieved the lowest Mean Squared Error (MSE) and Root Mean Squared Error (RMSE), indicating superior predictive accuracy compared to the other models.**
* CatBoost also exhibited the highest R-squared score, implying better fit to the data.
* Random Forest Regression and Gradient Boost Regression also performed relatively well, with similar MSE and RMSE values.
* K-nearest Neighbor (KNN) had the highest MSE and RMSE values, suggesting comparatively poorer predictive performance compared to the other models.

Across all models, the Root Mean Squared Error (RMSE) values are greater than or equal to the median house price, indicating that the models have room for improvement in reducing prediction errors.

**CatBoost Regression achieved the lowest Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) values, indicating superior predictive accuracy compared to the other models. Additionally, it exhibited the highest R-squared score, suggesting better fit to the data.**

Therefore, based on the evaluation metrics and the goal of minimizing prediction errors, the CatBoost Regression model is considered the better choice among the four models evaluated.

## **Result based on Residuals:**
**Based on the residuals, the CatBoost and RandomForest models stand out for their performance compared to the other models. Here's why:**

**Random Forest:** 
This model exhibits the smallest average residual (65,917.24) and the lowest average absolute residual (811,218.33) among all the models. These metrics indicate that, on average, the Random Forest model predicts house prices more closely to their actual values. This suggests that Random Forest is effective in capturing the underlying patterns in the data.

**CatBoost:** 
While CatBoost has a slightly higher average residual (-79,960.55) compared to Random Forest, it still demonstrates the lowest average absolute residual (658,119.68). This indicates that CatBoost makes relatively accurate predictions, albeit with a lower bias compared to Random Forest, as indicated by its lower average absolute residual.

***In summary, both Random Forest and CatBoost models perform well in predicting house prices, with Random Forest showing slightly better performance in terms of minimizing residuals and CatBoost showing a lower bias on the residuals***

Please visit project [website](https://sites.google.com/view/find-out-nyc-house-price/home) for more details of result and analysis.
