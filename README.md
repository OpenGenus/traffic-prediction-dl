# Traffic Prediction using Deep Learning

This repository contains code for implementing a deep learning model for traffic prediction. The code is based on the "Deep Learning for traffic prediction" article.

## Contents

- **Imports**: Import necessary libraries and packages for data manipulation, visualization, and modeling.
- **Exploratory Data Analysis (EDA)**: Explore the dataset by visualizing unique roadways, directions, and congestion patterns.
- **Data Engineering**: Prepare the data for training by performing feature engineering, one-hot encoding, and data standardization.
- **Model Building**: Create a deep learning model using TensorFlow's Keras API with dense layers.
- **Model Training**: Train the deep learning model on the preprocessed data and monitor the training progress using early stopping.
- **Model Evaluation**: Evaluate the trained model's performance on the validation set using mean squared error.
- **Visualization**: Visualize the predicted and actual congestion values for different roadways and directions.

## Usage

1. Install the required libraries using the following command:
> pip install numpy pandas matplotlib scikit-learn tensorflow
2. Download the dataset "train.csv" from the Kaggle competition "Tabular Playground Series - Mar 2022" and place it in the same directory as the code.
3. Run the provided Python script to execute the entire pipeline.

## About
This repository demonstrates the implementation of a deep learning model for traffic prediction based on the provided dataset. The code showcases steps from data preprocessing to model evaluation and visualization of predictions.

