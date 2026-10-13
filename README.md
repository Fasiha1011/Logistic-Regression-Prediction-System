# Logistic-Regression-Prediction-System

## Overview
This project implements Logistic Regression using two different datasets: Diabetes Prediction and Bank Marketing Prediction. It provides interactive user interfaces using Gradio and Flask, allowing users to enter data and receive predictions.

## Features
- Implements Logistic Regression on two datasets.
- Predicts diabetes using medical-related features.
- Predicts customer subscription using bank marketing data.
- Splits datasets into training and testing sets.
- Evaluates models using accuracy, confusion matrix, precision, recall, and F1-score.
- Provides an interactive Gradio interface.
- Provides a web interface using Flask.
- Displays prediction results based on user input.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Gradio
- Flask
- HTML and CSS

## Project Files
- `Logistic_Regression.ipynb` — Notebook containing data preparation, model training, evaluation, and interface code.
- `diabetes.csv` — Dataset used for diabetes prediction.
- `bank-additional-full.csv` — Dataset used for bank marketing prediction.
- `requirements.txt` — Required Python libraries.
- `README.md` — Project documentation.

## Models and Datasets

### 1. Diabetes Prediction
Uses eight input features, including pregnancies, glucose, blood pressure, BMI, and age, to predict the diabetes outcome.

Dataset size: 768 records.

### 2. Bank Marketing Prediction
Uses customer age, account balance, contact duration, and campaign contacts to predict whether a customer is likely to subscribe to a term deposit.

Dataset size: 45,211 records.

Both models use Logistic Regression with feature scaling. The Bank Marketing model uses balanced class weights to help address class imbalance.

## Model Evaluation
Initial model accuracy before applying balanced class weights:

| Dataset | Accuracy |
|---|---:|
| Diabetes Prediction | 75.32% |
| Bank Marketing | 88.59% |

The Bank Marketing accuracy may change after applying balanced class weights.

## How to Run
1. Install Anaconda Navigator and open Jupyter Notebook.
2. Install the required libraries using:

   `pip install pandas numpy scikit-learn gradio flask`

3. Place both CSV datasets in the expected project folder.
4. Open `Logistic_Regression.ipynb`.
5. Run the notebook cells in order.
6. Run the Gradio cell to launch the Gradio interface.
7. Run the Flask cell to launch the Flask interface.
8. Open `http://127.0.0.1:5001` to access the Flask application.

Keep the notebook running while using either interface.

## Conclusion
This project demonstrates the application of Logistic Regression to two binary classification tasks and provides interactive predictions through Gradio and Flask.

## Author
Fasiha Faraz
