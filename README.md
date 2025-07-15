
# 💳 Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. It is designed to learn from historical transaction patterns and identify anomalies that indicate potential fraud.

## 🚀 Overview

- **Input**: Credit card transaction data with anonymized features and class labels.
- **Output**: Classification of transactions as **fraudulent (1)** or **genuine (0)**.
- **Machine Learning Models Used**:
  - XGBoost Classifier
  - Feed Forward Neural Network (FFNN)

## 🧠 Key Features

- Handles **imbalanced datasets** effectively to avoid biased results.
- Implements **robust ML algorithms** for accurate classification.
- Evaluates models using standard performance metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

## 📁 Project Structure

```
credit-card-fraud-detection/
├── credit_fraud.py        # XGBoost model implementation
├── model_building.py             # Neural Network model using Keras/TensorFlow
└── README.md                         # Project documentation
```

> Rename files here if they are different in your directory.

## ⚙️ Installation & Setup

1. **Clone the repository**:
```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

2. **Install the required libraries**:
```bash
pip install -r requirements.txt
```

```
> pandas
> numpy
> scikit-learn
> xgboost
> tensorflow
> matplotlib
> seaborn

```




## 📊 Dataset Used

The project uses the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud), which contains real-world anonymized transactions made by European cardholders in September 2013. The dataset has:
- 284,807 transactions
- 492 fraud cases (0.17%)
- Features: `V1` to `V28`, `Amount`, and `Class`

## 📈 Model Performance (Example Results)

| Model              | Accuracy | Precision | Recall | F1 Score |
|-------------------|----------|-----------|--------|----------|
| XGBoost Classifier| 99.2%    | 96.8%     | 92.6%  | 91.0%    |
| Neural Network     | 98.6%    | 94.7%     | 90.3%  | 88.3%    |

> Replace these values with actual results from your models.

## 📌 Future Enhancements

- Improve neural network tuning using GridSearch/RandomSearch.
- Integrate real-time stream detection using Kafka or Spark.
- Build a UI dashboard for visual fraud monitoring.

## 👩‍💻 Author

**Ishita Verma**  
Aspiring Data Scientist | Machine Learning Enthusiast  | SDE 




---

Feel free to ⭐ this project if you found it useful!
