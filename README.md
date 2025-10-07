# 💳 Credit Card Fraud Detection Project

## 📖 Project Overview

This project is an end-to-end machine learning model that detects fraudulent credit card transactions. I built this to practice data preprocessing, handling imbalanced data using SMOTE, and comparing the performance of different classification models like Logistic Regression, Random Forest, and XGBoost.

## 📊 Dataset

The project uses the "Credit Card Fraud Detection" dataset from Kaggle.

-   **Link**: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## 🚀 Features
- Complete machine learning pipeline for fraud detection
- Handles extreme class imbalance using appropriate evaluation metrics
- Compares multiple algorithms: Logistic Regression, Random Forest, and XGBoost
- Includes preprocessing, model training, and evaluation

## 📂 Folder Structure

```
credit-card-fraud-detection/
├── images/               # Visualizations 
├── models/               # Trained models (.pkl files)
├── notebooks/            # Jupyter notebook with full implementation
├── .gitignore
├── README.md            
└── requirements.txt      # Dependencies
```
---

## 🛠️ Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/arshadmurtaza03/credit-card-fraud-detection.git
    cd credit-card-fraud-detection
    ```

2.  **Create and activate a virtual environment:**
    ```bash
        # Linux/macOS
    python3 -m venv venv
    source venv/bin/activate

        # Windows
    python -m venv venv
    venv\Scripts\activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Download the dataset** from the Kaggle link above and place it in the `data/` directory.

5. **Run the Jupyter Notebook**
    ```bash
    jupyter notebook notebooks/fraud_detection.ipynb
    ```

## Usage

All the code and analysis can be found in the Jupyter Notebook inside the `notebooks/` directory.

---

## Model Evaluation Results

The models were evaluated based on their ability to correctly identify fraudulent transactions (Recall) while maintaining reasonable precision.

| Model               | Precision (Fraud) | Recall (Fraud) | F1-Score (Fraud) |
| ------------------- | ----------------- | -------------- | ---------------- |
| Logistic Regression | 0.058             | 0.918          | 0.109            |
| Random Forest       | 0.871             | 0.827          | 0.848            |
| XGBoost             | 0.728             | 0.847          | 0.783            |

---
## How to cite / contact

Author: Arshad Murtaza
GitHub: https://github.com/arshadmurtaza03/credit-card-fraud-detection.git
Email: arshadmurtaza2016@gmail.com




