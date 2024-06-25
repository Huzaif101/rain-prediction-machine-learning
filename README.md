# rain-prediction-machine-learning
# Weather Prediction Models Using Machine Learning

This repository contains a comprehensive analysis and implementation of various machine learning models to predict weather conditions, specifically focusing on predicting whether it will rain tomorrow. The models used include Linear Regression, K-Nearest Neighbors (KNN), Decision Trees, Logistic Regression, and Support Vector Machines (SVM).

## Table of Contents
- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Models Implemented](#models-implemented)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Weather prediction is a critical task that impacts various sectors such as agriculture, aviation, and daily planning. This project aims to build and compare different machine learning models to accurately predict whether it will rain tomorrow based on historical weather data.

## Data Preprocessing
The dataset used in this project includes various features such as temperature, humidity, wind speed, and direction. The data preprocessing steps involve:
- Handling missing values
- Encoding categorical variables using one-hot encoding
- Splitting the data into training and testing sets

## Models Implemented
The following machine learning models have been implemented and trained on the dataset:
1. **Linear Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Decision Tree**
4. **Logistic Regression**
5. **Support Vector Machine (SVM)**

## Evaluation Metrics
To evaluate the performance of the models, we use the following metrics:
- Accuracy Score
- Jaccard Index
- F1-Score
- Log Loss (for Logistic Regression)
- Mean Absolute Error (MAE) (for Linear Regression)
- Mean Squared Error (MSE) (for Linear Regression)
- R2-Score (for Linear Regression)

## Results
The models are evaluated based on the above metrics, and the results are compared to determine the most effective model for weather prediction.

## Installation
To run the code in this repository, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/weather-prediction-models.git
    ```
2. Navigate to the project directory:
    ```bash
    cd weather-prediction-models
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
You can run the Jupyter Notebook to see the entire process of data preprocessing, model training, and evaluation:
1. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open the `weather_prediction.ipynb` file and run the cells to see the results.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or new features.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
