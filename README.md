

**House Price Prediction using Gradient Boosting**
This repository contains a machine learning pipeline designed to predict residential real estate prices based on physical attributes and location. The project is implemented in Python and optimized for execution in Google Colab.

**📌 Project Objective**
The goal of this project is to develop a robust regression model that can estimate house prices with high accuracy by processing both numerical data (square footage, bedrooms) and categorical data (neighborhood/location).

**Key Techniques:**

One-Hot Encoding: Converting categorical location data into machine-readable binary features.

Feature Scaling: Using StandardScaler to normalize numerical ranges.

Gradient Boosting Regressor: An ensemble learning method that builds trees sequentially to minimize prediction error.

**📊 Pipeline Workflow**
Data Ingestion: Uploading local .csv files via Google Colab's file API.

Preprocessing: * Handling missing values.

Encoding categorical strings into numerical vectors.

Scaling features to ensure model stability.

Model Training: Training a Gradient Boosting model to capture non-linear relationships.

Evaluation: Measuring performance using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

Visualization: Plotting Actual vs. Predicted values to identify outliers.

📈 Results
The model's performance is visualized through a scatter plot where the proximity of points to a 45 
∘
  diagonal line indicates the accuracy of the predictions.

MAE: Shows the average dollar amount the model is "off" by.

RMSE: Highlights if the model is making significant errors on luxury or outlier properties.

🚀 How to Run
Open the .ipynb file in Google Colab.

Run the first cell to trigger the file upload prompt.

Upload your house price dataset (CSV).

Execute the remaining cells to view the analysis and charts.
