# codsoft_task_Credit_Card_Fraud_Detection
# Credit Card Fraud Detection Project

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Credit card fraud is a significant issue that can result in financial losses for individuals and businesses. The goal of this project is to build a predictive model that can identify whether a transaction is fraudulent or not based on various features.
![Screenshot (49)](https://github.com/TechZainShahzad/codsoft_task5_Credit_Card_Fraud_Detection/assets/136337895/0c29ceff-ae29-4bbb-94f2-bb58989e74f4)

## Dataset
The dataset used in this project is obtained from a credit card transactions dataset, which contains a mixture of fraudulent and non-fraudulent transactions. The dataset includes features such as transaction amount, time, and anonymized numerical features derived from the credit card transactions.
![Screenshot (50)](https://github.com/TechZainShahzad/codsoft_task5_Credit_Card_Fraud_Detection/assets/136337895/b8cf2697-4c8a-4693-9b64-1f4f856ab1bd)

## Data Preprocessing
1. **Handling Imbalanced Data:** The dataset is examined to understand the distribution of fraud and non-fraud cases. Techniques such as oversampling or undersampling may be applied to address class imbalance.
2. **Feature Scaling:** Standard scaling is applied to the 'Amount' feature to ensure that all features have a similar scale, which is essential for many machine learning algorithms.
![Screenshot (51)](https://github.com/TechZainShahzad/codsoft_task5_Credit_Card_Fraud_Detection/assets/136337895/e6342e10-4565-424a-a469-2591cc76ce67)

## Model Training
A Random Forest Classifier is employed for training the model. The dataset is split into training and testing sets, and the model is trained on the training set. The Random Forest Classifier is chosen for its ability to handle complex relationships in data and provide insights into feature importance.

## Evaluation Metrics
The model's performance is evaluated using various metrics, including:
- **Confusion Matrix:** A table showing the true positive, true negative, false positive, and false negative predictions.
- **Precision:** The ratio of correctly predicted positive observations to the total predicted positives.
- **Recall:** The ratio of correctly predicted positive observations to the total actual positives.
- **F1 Score:** The harmonic mean of precision and recall, providing a balanced measure.
- **Accuracy:** The ratio of correctly predicted observations to the total observations.
![Screenshot (52)](https://github.com/TechZainShahzad/codsoft_task5_Credit_Card_Fraud_Detection/assets/136337895/9652f46e-ea72-4552-9acf-d38b84503272)

## Results
The F1 score is used as the primary metric for evaluating the model's performance. The confusion matrix and other metrics provide a comprehensive understanding of how well the model performs in detecting fraudulent transactions.

## Usage
1. **Clone the Repository:** Clone this repository to your local machine.
2. **Install Dependencies:** Make sure to install the required Python libraries specified in the `requirements.txt` file.
3. **Run the Notebook/Script:** Execute the provided Jupyter notebook or Python script to train the model and evaluate its performance.

Feel free to explore and contribute to the project. Your feedback and contributions are highly appreciated!
