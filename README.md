# House-Price-Prediction
Employing Python to execute Random Forest (RF), and Extreme Gradient Boosting (XGBoost). The primary objective was to identify the algorithm that provides the more accurate prediction of house prices.
# Background and Feature Importance
Features, otherwise known as variables, are properties of a data set and are used as inputs for machine learning models. Although they are typically numeric, they can also be strings. Selecting relevant and reliable features is essential for algorithms, making features one of the most important components in machine learning modeling

The quality of features directly impacts model predictions, further emphasizing the importance of feature selection in machine learning. By measuring feature importance, we can determine which features contribute most to a model's predictions. Feature importance techniques assign a score to each input feature based on its usefulness in predicting a target variable, indicating the degree of usefulness for a current model and prediction.

# Data Set
The dataset included both numeric and binary variables. The number of rooms, kitchens, and French doors were all numerical features. Binary features, represented by 0 for "no" and 1 for "yes," included whether the house has a backyard, is furnished, is painted green, has a wood floor, has security, and has club access.

# Linear, RF, KNN, MAE
To predict and extract the necessary information and insights from a dataset, various machine learning algorithms can be utilized. In this case, the dataset was subjected to two major algorithmic tests, employing Python to execute Linear Regression, Random Forest (RF), and Extreme Gradient Boosting (XGBoost). The primary objective was to identify the algorithm that provides the more accurate prediction of house prices. The comparison was based on the Mean Absolute Error (MAE), with the general understanding that a low MAE indicates a better prediction while a larger MAE implies otherwise.

<img width="414" alt="L KNN RF" src="https://github.com/user-attachments/assets/35ac3e04-675c-4425-ae24-ee06d68e6044">

Information provided in Figures 1,2 and 3 reveals the values between the truth and predicted regression values of the two selected algorithms. The figures show that the values are closer in LR, followed by RF and lastly KNN. Likewise, the MAE score of 13 for LR,172 for RF, and 471 for KNN indicates that the magnitude of difference between the prediction and the true value of the observation is lower in LR and RF than KNN. Given this, LR  is considered the most suitable context for predicting house prices given the data set. Furthermore, the value of the R-squared of 0.999 and 0.947 for RF and KNN respectively also lends credence to this. While they are both “good” R-squared values, it however indicates that 99.9% and 94.7% of the variance of the dependent variable (house prices) is explained by the variance of the independent variable (features).

<img width="364" alt="MAE" src="https://github.com/user-attachments/assets/338a2076-3768-4297-a19c-d7b169073cf7">

<img width="313" alt="MAE png" src="https://github.com/user-attachments/assets/d17d070d-7487-46f9-a299-81252315f589">

# Ranking Feature Importance
A summary of feature importance and ranking for the LR and RF algorithms are presented image

<img width="377" alt="FEATURE IMPORTANCE" src="https://github.com/user-attachments/assets/f9f8073b-7977-4dc6-9d41-dd602222cb06">
