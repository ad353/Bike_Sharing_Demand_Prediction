# Bike_Sharing_Demand_Prediction

## Problem Statement

In numerous urban areas, rental bikes have been introduced to improve the convenience of mobility. Ensuring the timely availability and accessibility of these rental bikes to the public is of paramount importance, as it reduces waiting times. Consequently, ensuring a consistent and adequate supply of rental bikes to the city emerges as a significant challenge. The critical aspect involves forecasting the hourly demand for bike counts to maintain a stable supply of rental bikes.

## Attribute Information

- Date - Date
- Rented Bike Count - Count of bikes rented at each hour
- Hour - Hour of the day
- Temperature(°C) - Temprature of the day
- Humidity(%) - Humidity measure
- Wind speed (m/s) - Wind speed
- Visibility (10m) - Visibility measure
- Dew point temperature(°C) - Dew point temperature measure
- Solar Radiation (MJ/m2) - Solar Radiation measure
- Rainfall(mm) - Rainfall in mm
- Snowfall (cm) - Snowfall measure
- Seasons - Seasons
- Holiday - Whether a holiday or not
- Functioning Day - Whether a functioning day or not

## Key Features 

- Exploratory Data Analysis (EDA): Conducted comprehensive analysis of the dataset, exploring its structure, data types, and statistical summaries. Identified key features and patterns that impact bike demand, such as time, temperature, and weather conditions.

- Data Cleaning and Preprocessing: Cleaned the dataset by handling duplicate values, missing data, and outliers. Ensured the integrity and quality of the data for accurate modeling.

- Feature Engineering: Engineered relevant features and transformed variables to capture meaningful information for prediction. Performed feature encoding, handled multicollinearity, and applied transformations to improve model performance.

- Model Training and Evaluation: Trained and evaluated various regression models using a scaled feature set. Employed techniques such as Linear Regression, Ridge Regression, Lasso Regression, Decision Tree Regression, Random Forest Regression, Gradient Boosting Regression, and hyperparameter tuning to optimize model performance.

- Performance Metrics: Evaluated the models using industry-standard metrics such as R-squared, adjusted R-squared, and mean squared error (MSE). Selected the final model based on its performance and ability to make accurate predictions.

## Algorithms Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression


## Conclusion

- The demand for bikes is higher in the summer season and lower in the winter season.
- There is high demand on working days compared to non-working days.
- The demand for bikes is high in June and lower in January.
- There is high demand at 8 o'clock in the morning and 6 o'clock in the evening.
- Multicollinearity has been observed between the temperature and dew point temperature variables.
- After conducting various modeling techniques, including linear regression, decision tree, random forest, and gradient boosting, we achieved the highest accuracy of 90% using gradient boosting.
