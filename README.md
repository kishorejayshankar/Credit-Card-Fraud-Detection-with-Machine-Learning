# Credit-Card-Fraud-Detection-with-Machine-Learning
# Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning techniques. The goal is to identify potential fraudulent activities so that customers are not charged for unauthorized purchases.

## Overview

Credit card fraud is a significant problem that affects both customers and financial institutions. Detecting fraudulent transactions in real-time is crucial to prevent financial losses and maintain customer trust. However, it poses several challenges, including:

- Enormous data processing requirements.
- Imbalanced data, where fraudulent transactions are rare compared to legitimate ones.
- Privacy concerns with sensitive transaction data.
- Misclassified data and adaptive techniques used by scammers.

## Approach

To tackle these challenges, we employ the following strategies:

1. **Fast and Simple Model**: We use machine learning models that are efficient and quick to respond to fraudulent activities.

2. **Handling Imbalanced Data**: We address the imbalance in the dataset using techniques such as resampling or algorithm adjustments to give more weight to minority class samples.

3. **Privacy Protection**: Dimensionality reduction techniques are applied to protect the privacy of users while retaining important information.

4. **Data Validation**: We ensure the reliability of the data source by cross-checking and validating the dataset to minimize misclassified transactions.

5. **Model Interpretability**: By keeping the model simple and interpretable, we can quickly adapt to new fraud patterns and deploy updated models as needed.

## Dataset

The dataset used in this project is obtained from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains anonymized credit card transactions labeled as fraudulent or legitimate.

## Project Structure

- `credit_card_fraud_detection.ipynb`: Jupyter notebook containing the code for data analysis, model training, and evaluation.
- `credit.csv`: Dataset containing credit card transaction data.

## Installation

To run the notebook locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/username/credit-card-fraud-detection.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook `credit_card_fraud_detection.ipynb` and execute the cells.

## Results

After training our model, we achieved the following results:

- Accuracy: 99.95%
- Precision: 98.67%
- Recall: 75.51%
- F1-Score: 85.55%
- Matthews Correlation Coefficient: 86.30%

## Conclusion

Our model demonstrates high accuracy in detecting fraudulent credit card transactions. By leveraging machine learning techniques and addressing various challenges, we can effectively protect customers and financial institutions from fraudulent activities.
