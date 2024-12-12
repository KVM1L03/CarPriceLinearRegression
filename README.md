# Car Price Prediction

This project uses machine learning to predict the selling price of used cars based on various features. It utilizes a Linear Regression model trained on a dataset of car data.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ERNb5ZgU3gjIBBu4Shu4I9m60O-IWDK3?usp=sharing)

## Table of Contents

- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Usage](#usage)


## Dataset

The dataset used in this project is the "Vehicle Dataset from CarDekho" available on Kaggle. It contains information about used cars, including features like year, present price, kilometers driven, fuel type, seller type, transmission, and owner.

**Link to Dataset:** [https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?select=car+data.csv](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?select=car+data.csv)


## Data Preprocessing

Before training the model, the following preprocessing steps are performed:

1. **Feature Selection:** Relevant features are selected for predicting the car price.
2. **One-Hot Encoding:** Categorical features (Fuel_Type, Seller_Type, Transmission) are converted into numerical representations using one-hot encoding.
3. **Data Splitting:** The dataset is split into training and testing sets to evaluate the model's performance.


## Model Training

A Linear Regression model is used for predicting the car price. The model is trained using the training dataset.


## Model Evaluation

The model's performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). These metrics provide insights into the accuracy and reliability of the predictions.


## Usage

To use this project, follow these steps:

1. Upload the dataset (`car_data.csv`) to your Google Colab environment.
2. Run the code cells in the notebook cell by cell.
3. The model will be trained and evaluated, and the results will be displayed.
4. You can modify the code to experiment with different features or models.
