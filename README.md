# Housing Price Prediction Project

This repository contains a project that predicts housing prices using data analysis and machine learning techniques. The project uses the Ordinary Least Squares (OLS) regression model to analyze and predict the median house value based on various features in the dataset.

## Project Structure

- **1_eda.ipynb**: This notebook performs exploratory data analysis (EDA) on the housing dataset. It includes visualization and statistical analysis of the key features.
- **2_main.ipynb**: This notebook contains the main analysis and modeling process, including data preprocessing, model training, and evaluation using OLS regression.

## Dataset

The dataset used in this project is provided in `housing.csv`, which contains information about various housing attributes, such as `longitude`, `latitude`, `median_income`, `total_rooms`, etc., as well as the `median_house_value` which is the target variable.

## Getting Started

### Prerequisites

Ensure that Python 3.x is installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://git@github.com:Vinald/House_Price_Prediction.git
   cd House_Price_Prediction
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Open and run the `1_eda.ipynb` notebook to explore the dataset and visualize key trends and relationships.
2. Open and run the `2_main.ipynb` notebook to preprocess the data, train the OLS regression model, and evaluate its performance.

### Models Used

- **Ordinary Least Squares (OLS) Regression**: This linear regression technique is used to predict the `median_house_value` based on other features in the dataset.
- **Data Preprocessing**: Standardization of features using `StandardScaler`.

### Results

The model's performance is evaluated using:

- **R-squared**: Measures how well the model fits the data.
- **Root Mean Squared Error (RMSE)**: Evaluates the difference between predicted and actual values.

### Visualizations

The project includes the following visualizations:

- Histograms and boxplots of key features
- Scatter plots to show relationships between features
- Residual plots to evaluate the OLS regression model

### Conclusion

This project demonstrates the use of OLS regression for predicting housing prices. The results highlight the significance of various housing features in predicting the median house value.

### License

GNU GENERAL PUBLIC LICENSE
