# 💳 Credit Card Fraud Detection using Machine Learning

## 📖 Overview

This project aims to detect fraudulent credit card transactions using Machine Learning techniques. It uses the popular Credit Card Fraud Detection dataset and compares the performance of multiple classification algorithms to identify suspicious transactions accurately.

The project includes:
- Data preprocessing
- Duplicate removal
- Exploratory Data Analysis (EDA)
- Model training
- Fraud prediction
- Model evaluation

---

## 🚀 Features

- 📊 Loads and analyzes the credit card transaction dataset
- 🧹 Removes duplicate records
- 🔍 Performs exploratory data analysis
- 🤖 Implements multiple Machine Learning algorithms:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
- 📈 Evaluates model performance using classification metrics
- 💳 Predicts whether a transaction is **Fraud** or **Normal**

---

## 🗂️ Project Structure

```
Credit-Card-Fraud-Detection/
│
├── creditcard.csv               # Dataset
├── LogisticRegression.ipynb     # Logistic Regression model
├── DecisionTree.ipynb           # Decision Tree model
├── RandomForest.ipynb           # Random Forest model
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

This project uses the **Credit Card Fraud Detection** dataset, which contains anonymized credit card transactions with features generated using PCA transformation.

### 📥 Download the Dataset

The dataset is too large to be included in this repository. You can download it from Kaggle:

**🔗 https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud** :contentReference[oaicite:0]{index=0}

After downloading:
1. Extract the dataset (if compressed).
2. Place the `creditcard.csv` file in the root directory of this project.
3. Run the Jupyter notebooks to train and evaluate the models.

### Important Columns

| Column | Description |
|---------|-------------|
| Time | Seconds elapsed between transactions |
| V1 - V28 | PCA-transformed confidential features |
| Amount | Transaction amount |
| Class | Target variable (0 = Legitimate, 1 = Fraud) |

The dataset contains **284,807 transactions**, of which **492 are fraudulent**, making it a highly imbalanced binary classification problem that is widely used for fraud detection research. :contentReference[oaicite:1]{index=1}

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/palshrenik/Credit-Card-Fraud-Detection-ML.git
```

Navigate to the project folder:

```bash
cd Credit-Card-Fraud-Detection-ML
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. Download or place `creditcard.csv` in the project directory.
2. Open any notebook:
   - `LogisticRegression.ipynb`
   - `DecisionTree.ipynb`
   - `RandomForest.ipynb`
3. Run all cells in Jupyter Notebook or VS Code.
4. View the evaluation metrics and predictions.

---

## 🧠 Machine Learning Models

### Logistic Regression
- Simple and efficient linear classification model.
- Suitable as a baseline for fraud detection.

### Decision Tree
- Learns decision rules from the data.
- Easy to interpret and visualize.

### Random Forest
- Ensemble learning algorithm based on multiple decision trees.
- Typically provides better generalization and robustness.

---

## 📈 Workflow

1. Load dataset
2. Remove duplicates
3. Explore and analyze data
4. Split data into training and testing sets
5. Train machine learning model
6. Predict transaction classes
7. Evaluate model performance

---

## 🎯 Objective

To accurately classify credit card transactions as **fraudulent** or **legitimate**, helping financial institutions reduce fraud-related losses and improve transaction security.

---

## 📌 Future Improvements

- Add XGBoost and LightGBM models
- Hyperparameter tuning
- Handle class imbalance using SMOTE
- Deploy using Flask or Streamlit
- Build a web interface for real-time fraud prediction

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
