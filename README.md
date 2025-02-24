# CAR_DEKHO_PROJECT
Car Dekho Project using Python
Problem Statement:
The used car market in India is a dynamic and ever-changing landscape. Prices can fluctuate wildly based on a variety of factors including the make and model of the car, its mileage, its condition and the current market conditions. As a result, it can be difficult for sellers to accurately price their cars.

Approach:
We propose to develop a machine learning model that can predict the price of a used car based on its features. The model will be trained on a dataset of used cars that have been sold on Cardekho.com in India. The model will then be able to be used to predict the price of any used car, given its features.

Objective
To build suitable Machine Learning Model for Used Car Price Prediction.

Benefits:
The benefits of this solution include:

Sellers will be able to more accurately price their cars which will help them to sell their cars faster and for a higher price.
Buyers will be able to find cars that are priced more competitively.
The overall used car market in India will become more efficient.

Project Summary: Used Car Price Prediction

In this project, we developed a machine learning model to predict used car prices in India using data from Cardekho.com. The model addresses the challenges of pricing in a volatile market influenced by factors such as mileage, engine specifications, and car condition.

Key Steps:

Data Cleaning & Preprocessing:

Extracted numerical values from columns containing units (e.g., mileage, engine, max_power) using regular expressions.
Removed the redundant 'car_name' column and dropped rows with missing values to ensure data consistency.
Applied a log transformation to the target variable (selling_price) to reduce skewness.
Feature Engineering & Transformation:

Defined numerical features (vehicle_age, km_driven, mileage, engine, max_power, seats) and categorical features (brand, model, seller_type, fuel_type, transmission_type).
Constructed a preprocessing pipeline using a ColumnTransformer to scale numerical features (via StandardScaler) and encode categorical features (using OneHotEncoder), ensuring robust feature representation.
Model Building:

Integrated the preprocessing steps with a RandomForestRegressor into a single pipeline.
Trained the model on 80% of the data while reserving 20% for testing, achieving high performance as evidenced by the evaluation metrics.
Evaluation & Prediction:

Evaluated the model using RMSE and R² score to assess accuracy.
Demonstrated the model’s predictive capability by estimating the price of a sample used car, providing sellers and buyers with a reliable price prediction tool.
Benefits:

Sellers can price their cars more accurately, reducing the time to sale and potentially achieving higher prices.
Buyers gain access to more competitively priced vehicles, improving market efficiency.
This approach not only simplifies the pricing process but also contributes to a more transparent and efficient used car market in India.
