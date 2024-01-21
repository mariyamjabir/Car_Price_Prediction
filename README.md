# Car_Price_Prediction

## Objective
The objective of this project is to build a machine learning model to predict the prices of used cars based on various features such as the car's specifications, location, fuel type, transmission, and owner type. The goal is to create an accurate and reliable model that can assist in estimating the market value of a used car.

## Data Collection
The dataset used in this machine learning project was obtained from Kaggle, a prominent platform for datasets.  The dataset includes information about different used cars, such as their specifications, location, fuel type, transmission type, owner type, and price. The data is collected to analyze patterns and relationships between different features and the price of the cars.

## Methodology
The methodology involves several key steps, including data exploration, preprocessing, feature engineering, model training, and evaluation.

### Data Exploration
The initial step involves loading the dataset, exploring its structure, and visualizing the distribution of car prices using a histogram. The histogram reveals a right-skewed distribution, indicating the presence of varying price ranges and potential outliers.

### Dummy Encoding
Categorical variables such as location, fuel type, transmission, and owner type are dummy encoded to convert them into a format suitable for machine learning models. This step involves creating binary columns for each category and dropping one of them to avoid multicollinearity.

### Data Preprocessing
The dataset undergoes preprocessing to handle missing values, convert string-based numerical features into numeric types, and address potential outliers. Mileage, power, and engine features are cleaned and converted to numeric types. Missing values are imputed using mean values for numerical features and mode for categorical features.

### Model Training
The dataset is split into training and testing sets, and a Random Forest Regressor model is trained using the training set. Standard scaling is applied to the features to ensure consistent scales for model training.

### Model Selection & Evaluation
The Random Forest Regressor is chosen as the predictive model. The model is evaluated using metrics such as Mean Squared Error (MSE) and R-squared on the test set. The evaluation results provide insights into the model's performance in predicting car prices.

## Conclusion
The machine learning model, based on the Random Forest Regressor, demonstrates its ability to predict car prices using the provided features. The evaluation metrics, including MSE and R-squared, indicate the model's effectiveness. The model can be further fine-tuned or used as a foundation for more complex models to enhance prediction accuracy. Overall, the project provides a framework for predicting used car prices, aiding both sellers and buyers in estimating the fair market value of a car based on its specifications and other relevant factors.
