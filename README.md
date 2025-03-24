## CreditCard Fraud Detection

Welcome to the **CreditCard Fraud Detection** project! This project aims to develop a robust machine learning model to detect fraudulent credit card transactions. By using advanced techniques such as **SMOTE** for handling class imbalance, we strive to build an efficient and accurate model.

---

### Dataset

The dataset used for this project is publicly available and can be accessed via Kaggle. It contains transaction details and labels each transaction as legitimate or fraudulent.

- **Source:** [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection)
  
- **Features:**
  - `Time`: Time of the transaction
  - `V1` to `V28`: Transaction features (anonymized)
  - `Amount`: The monetary value of the transaction
  - `Class`: 
    - `0`: Legitimate transaction
    - `1`: Fraudulent transaction

- **Size:** ~284,807 transactions

---

### Requirements

To run this project, ensure you have the following:

- **Python version:** 3.8+
- **Required Libraries:**
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `imbalanced-learn`

---

### Installation

To install the necessary libraries, use the following command:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn
```

### Usage
Clone the repository:


```
git clone <repository_url>
```
```
cd <project_directory>
```
Update Dataset Path:

In the code, update the file_path variable to the location where your dataset is stored.

Run the Script:

Execute the script to train and evaluate the machine learning model.

### Model Details
Model: Random Forest Classifier
Balancing Technique: SMOTE (Synthetic Minority Over-sampling Technique), UnderSampling, OverSampling

Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - AUC-ROC

### Future Enhancements
- Hyperparameter Tuning: Optimize model performance using GridSearchCV or RandomizedSearchCV.
- Feature Engineering: Investigate additional features like transaction frequency, or location-based data.
- Real-time Deployment: Aim for real-time transaction monitoring and fraud detection integration.
