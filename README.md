Used Car Price Prediction

This project focuses on estimating the price of used cars using machine learning techniques. The goal is to build a model that can make accurate predictions based on various features of a car.

What’s Included
The data is first cleaned and prepared using pandas to ensure everything is in a usable format. Since some of the features are categorical, OneHotEncoder is used to convert them into numerical values that the model can understand.

For the prediction task, a Random Forest Regressor is used because of its ability to handle complex relationships in the data and provide reliable results.

Performance
The model performs quite well, achieving an R² score of 0.95, which indicates a strong fit to the data. The Mean Absolute Error (MAE) is around 1250, meaning the predictions are, on average, fairly close to the actual prices.

Tools & Technologies
Python
pandas
scikit-learn
matplotlib