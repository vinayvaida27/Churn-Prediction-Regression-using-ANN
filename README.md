# Churn Prediction Using Regression with ANN

visit link to see deployed model - https://vinayvaida27-churn-prediction-streamlit-regression-model-t1jiay.streamlit.app/

This repository contains a project focused on predicting customer churn using regression techniques with an Artificial Neural Network (ANN). The model is trained on a customer dataset and is optimized with early stopping to prevent overfitting. Additionally, the model is deployed using Streamlit, allowing for an interactive web application to predict churn based on input features.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Model Training](#model-training)
- [Deployment](#deployment)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Customer churn is a significant issue in many industries, where businesses lose clients or subscribers. This project aims to predict the likelihood of a customer leaving a service based on various features using an ANN regression model. The model is trained with early stopping to avoid overfitting and to ensure better generalization.

The model has been deployed using Streamlit, allowing users to input customer data and receive predictions through an easy-to-use web interface.

## Installation

To run this project locally, please follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/vinayvaida27/Churn-Prediction-Regression-using-ANN.git
   cd Churn-Prediction-Regression-using-ANN
      ```
Install the required packages:
```bash
pip install -r requirements.txt
      ```
Model Training
The ANN model was trained on the Churn_Modelling.csv dataset. Key steps in the training process include:

Data Preprocessing: The dataset was preprocessed, including normalization and encoding of categorical variables.
Model Architecture: A deep neural network was designed for regression tasks.
Early Stopping: Implemented to halt training when no significant improvement in validation loss is detected, thus preventing overfitting.
Saving the Model: The trained model is saved as model.h5 for later use in deployment.
Deployment
The trained model is deployed using Streamlit. The deployment allows users to interact with the model via a web interface. You can access the deployed model here.

To run the Streamlit app locally, use the following command:
```bash
streamlit run Streamlit_regression_model.py

      ```

Usage
Navigate to the deployed Streamlit app or run it locally as described above.
Input the customer data into the provided fields.
The model will predict the likelihood of churn, helping businesses make informed decisions.
Contributing
Contributions are welcome! Please fork this repository, create a new branch, and submit a pull request.

