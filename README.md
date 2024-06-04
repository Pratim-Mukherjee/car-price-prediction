# car-price-prediction

Dataset link:- https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?select=car+data.csv

In this project, we developed a Random Forest Regressor model to predict the current value of a car based on various parameters such as fuel type, number of owners, kilometers driven, and age. Our model achieved a Mean Absolute Error (MAE) of 0.85, a Mean Squared Error (MSE) of 4.07, and a Root Mean Squared Error (RMSE) of 2.02. 

We conducted hyperparameter tuning to optimize the model's performance and applied encoding techniques to handle categorical data effectively. The trained model was then serialized using the `pickle` module for later use.

To make our model accessible and user-friendly, we deployed it using Flask. The deployment involved creating a web interface that accepts input parameters in JSON format and returns the predicted car value in real-time. This end-to-end process, from model training to deployment, demonstrates the practical application of machine learning techniques in predicting car prices.
