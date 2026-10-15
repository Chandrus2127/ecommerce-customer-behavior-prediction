# E-Commerce Customer Behavior and Purchase Prediction

## Project Overview
This project analyzes online retail transaction data and uses a
Multi-Layer Perceptron (MLP) deep learning model to classify
customers based on their future purchasing activity.

## Objectives
- Clean and preprocess online retail data.
- Analyze customer purchasing patterns using visualizations.
- Create customer-level features from transaction records.
- Predict Low, Average, and High future purchasing activity.
- Evaluate the model using classification metrics and graphs.

## Dataset
Source: UCI Machine Learning Repository - Online Retail

https://archive.ics.uci.edu/dataset/352/online+retail

The original dataset contains online retail transactions.
The target classes are created from the number of distinct valid
purchase invoices during the final 30 days of the dataset period.

- Low: 0 future purchase invoices
- Average: 1 future purchase invoice
- High: 2 or more future purchase invoices

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- TensorFlow / Keras
- Google Colab

## Project Structure
- ecommerce_customer_prediction.ipynb: Main notebook
- evaluation_results/: Model metrics and predictions
- visualizations/: EDA charts and model evaluation graphs
- README.md: Project documentation
- requirements.txt: Python dependencies

## How to Run
1. Open the notebook in Google Colab.
2. Download the dataset from the UCI link above.
3. Upload the dataset when prompted, or update the notebook
   to load it from your chosen location.
4. Run the notebook cells in order.

## Model Evaluation
The project reports test loss, accuracy, weighted precision,
weighted recall, weighted F1-score, a classification report,
and a confusion matrix.

Actual evaluation values are available in evaluation_results/.

## Limitations
The prediction classes are engineered from historical transactions.
They indicate future purchasing activity within this dataset and
do not directly represent website visits or conversion rates.
