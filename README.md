🚗 Car Price Prediction — Random Forest Regression
📖 Overview

This project applies Random Forest Regression to predict car prices based on multiple features such as engine size, fuel type, horsepower, car body, and more.
It is a small practice project aimed at beginners who want to learn:

How to handle categorical variables

OneHotEncoding using scikit-learn

Applying Random Forest for regression tasks

Evaluating performance using RMSE, MAE, and R² Score

📂 Dataset

The dataset contains information about different car models with features like:

Car Name

Fuel Type

Aspiration

Door Number

Car Body

Drive Wheel

Engine Location

Engine Type

Cylinder Number

Fuel System

Numerical features (horsepower, weight, wheelbase, etc.)

Target Variable: Car Price

⚙️ Steps Involved

Data Preprocessing

Handled categorical columns using OneHotEncoding

Dropped irrelevant columns

Combined numerical + encoded features

Model Training

Implemented Random Forest Regressor using sklearn

Split data into training & testing

Evaluation Metrics

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

R² Score

📊 Model Performance
| Metric | Value   |
| ------ | -----   |
| RMSE   |3716.6066|
| R²     | 0.80063 |


🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

🚀 How to Run

Clone this repo

git clone https://github.com/ishanegi5/car-price-prediction-random-forest.git


Install dependencies

pip install -r requirements.txt


Run the Jupyter Notebook

jupyter notebook car_price_small_project.ipynb

📌 Results & Insights

Random Forest performed well in handling categorical + numerical features

Feature importance can be analyzed to see which attributes affect car prices the most

Good project for beginners to practice regression with mixed data types

📜 License

This project is open-source and available under the MIT License.
