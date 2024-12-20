# House Price Predictor

This project is a machine learning model implemented in Python that predicts house prices based on key features like square footage, number of bedrooms, and bathrooms. The prediction is powered by a linear regression model, and the application includes an interactive command-line interface for user input.

**Features**

Linear Regression Model: A simple yet effective regression model to predict house prices.

Interactive User Input: Users can input house details like square footage, bedrooms, and bathrooms to get a predicted price.

Data Visualization: Includes plots for residual analysis, predicted vs actual prices, and feature importance.

**Usage**

Ensure the dataset (train.csv) is available in the project directory. This dataset should contain columns like GrLivArea, BedroomAbvGr, FullBath, and SalePrice.

**Run the script:**

python house_price_predictor.py

Follow the interactive prompts to input the details of the house:

Enter square footage (e.g., 1500)

Enter the number of bedrooms (e.g., 3)

Enter the number of bathrooms (e.g., 2)

The predicted house price will be displayed.

## Visualization

The project includes code for:

Residual Analysis: Visualizes the distribution of residuals to assess model performance.

Prediction vs Actual Plot: Shows how well the predicted prices match actual prices.

Feature Importance: Displays the contribution of each feature in the model.

## Acknowledgments

The dataset used in this project was sourced from Kaggle.

Inspiration for this project was drawn from real estate price prediction challenges.
