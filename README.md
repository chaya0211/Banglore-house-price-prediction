# Banglore-house-price-prediction
This project predicts the price of residential properties in Bangalore based on factors such as location, area number of bedrooms, and number of bathrooms. It uses machine learning  to build a predictive model that estimates home prices with good accuracy from available housing data.

The dataset contains real estate data for properties in Bangalore, India, with features including:
Location
Total area (in square feet)
Number of bedrooms (BHK)
Number of bathrooms
Price (in lakhs ₹)

Technologies Used:
Python 3
NumPy – Numerical operations
Pandas – Data cleaning & manipulation
Matplotlib / Seaborn – Visualization
Scikit-Learn – Machine Learning (Linear Regression)
Jupyter Notebook – Interactive development environment

1. Data Loading & Exploration
Load the dataset using Pandas.
Explore data structure, missing values, and outliers.

2. Data Cleaning
Remove missing or duplicate records.
Handle outliers in price_per_sqft.
Clean inconsistent location names.

3. Feature Engineering
Convert categorical features (like location) into numeric form using one-hot encoding.
Create new features such as price per sqft for better model learning.

4. Model Building
Split the data into training and testing sets.
Train a Linear Regression model using Scikit-Learn.

Results & Insights:
Linear Regression performed well for most localities.
Feature engineering improved model accuracy significantly.
Model achieved consistent results across various cross-validation folds.
The model can now predict housing prices for any given location in Bangalore.



Perform k-fold cross-validation to evaluate model performance.
