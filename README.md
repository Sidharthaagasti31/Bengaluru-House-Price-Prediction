# Bengaluru-House-Price-Prediction
<div align='center'>
  <img src="https://github.com/Sidharthaagasti31/Bengaluru-House-Price-Prediction/assets/50338854/4a0dc9fb-8cd6-46e8-b730-f3896d3bbf25" , alt="house",height=80,width=80 >
  </div>



### Overview:
This project is focused on predicting house prices in Bengaluru, India using machine learning techniques. It utilizes a dataset containing various features such as location, total size,number of bathrooms, number of bedrooms, etc., to train a model that can estimate the price of a house.

### Dataset

The dataset used in this project is sourced from [kaggle](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data). It contains 13320 instances and 9 features. Some of the features include:

Location: The area where the house is situated.
Size: The size of the house in terms of the number of rooms.
total_sqft: The total area of the house in square feet.
Number of bathrooms: The number of bedrooms in the house as in 'bath' column .
Price: The target variable, i.e., the price of the house.

### Tools Used


### Methodology

The project follows the following steps to predict house prices:
1. Data Preprocessing: The dataset is cleaned and processed to handle missing values, outliers, and any inconsistencies.
2. Feature Engineering: Additional features are created or existing features are modified to enhance the predictive power of the model.
3. Exploratory Data Analysis (EDA): Visualizations and statistical analysis are performed to gain insights into the dataset and understand the relationships between different features.
4. Model Selection: Various regression models are considered and evaluated to determine the most suitable one for the task.
5. Model Training: The chosen model is trained using the preprocessed dataset.
6. Model Evaluation: The trained model is evaluated using appropriate metrics to measure its performance.
7. Predictions: The model is used to predict house prices for new, unseen data.

### Results
From this ML project after testing various model, we got Linear regression Model to be best situated for predicting price of house in bengaluru having cross_validation score above 80% which is pretty good . And after train we got R2_Score around 82%.


### Future Improvements
1. We have only considered few features , and droped few features like Balcony which may be more important for deciding the price of house.

2. We have only tested with few models like lasso, linearRegression, DecisiontreeRegression . But there are more Regression model out there which needed to be explore like SVR regression,Random Forest Regression,Gradient Boosting Regression (e.g., XGBoost, LightGBM),AdaBoost Regression etc.
     
     
