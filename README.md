# Predicting Taxi Fares in NYC

Welcome to the Taxi Fare Prediction project! This project walks through the end-to-end process of building a machine learning model that predicts taxi fares in New York City based on features like trip distance, passenger count, and pickup time.

## Overview

This project leverages PySpark to handle and process large-scale NYC taxi trip data. The goal is to train a regression model that predicts the `total_amount` of a taxi ride. The workflow includes data loading, feature engineering, model training and evaluation, and prediction generation using Linear Regression.

**Dataset Source:**  
[NYC Yellow Taxi Trip Data (January 2021)](https://github.com/DataTalksClub/nyc-tlc-data/releases/download/yellow/yellow_tripdata_2021-01.csv.gz)

## Algorithms and Accuracy

The Linear Regression algorithm was used in this project, and the model was evaluated using:

- **RMSE (Root Mean Squared Error):** 0.826  
- **R² Score:** 99.69%

This indicates a strong model fit and high predictive power.

## Tools and Technologies

Here are the tools and technologies used in this project:

- **Python & PySpark:** For distributed data processing and ML pipeline  
- **Google Colab:** Development environment used for writing and testing the code  
- **Pandas & NumPy:** Data manipulation and preprocessing  
- **Matplotlib & Seaborn:** Visualizing the data distributions and correlations  
- **MLlib (Spark):** For building and evaluating the regression model  
- **CSV Format:** Final predictions were saved and exported in CSV format

## Get Started

To explore and run this project:

1. Clone this repository to your local system.  
2. Open and run the notebook in Google Colab (recommended for PySpark compatibility).  
3. Use the provided taxi trip dataset and follow the cells for end-to-end processing and model training.  
4. Generate predictions and export them for further use or analysis.

## Usage

This model can be used to:

- Predict taxi fares based on trip details like pickup time, duration, and passenger count.  
- Perform bulk fare estimations using structured input datasets.  
- Serve as a base model for integrating real-time fare predictions in dashboards or apps.

## Sample Output

**RMSE:** 0.8259  
**R²:** 0.9969

These metrics indicate that the model explains ~99.7% of the variance in the fare amount with minimal prediction error.

## Contact

If you have questions or suggestions, feel free to connect:

- **LinkedIn:** [iajithks](https://www.linkedin.com/in/iajithks/)

Happy Exploring!
