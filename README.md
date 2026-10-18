# 🗳️ Election Outcome Prediction and Trend Forecasting

Predicting Indian General Election outcomes and voting trends using Machine Learning classifiers and Time Series forecasting models.

---

## 📌 Project Overview
This project analyzes historical election data from the **2019 Indian General Elections (Lok Sabha)** (`LS_2.0.csv`) to:
1. **Predict Candidate Victory:** Classify whether a candidate will win or lose based on candidate profiles, party affiliation, assets, liabilities, criminal cases, education, and constituency voter dynamics.
2. **Forecast Vote Share Trends:** Utilize time series models to analyze and forecast state-wise vote share and voter turnout trends.

---

## 🛠️ Models & Techniques Used

### 1. Machine Learning Classifiers
- **Logistic Regression** – Baseline classification for election win probability.
- **Random Forest Classifier** – Ensemble decision-tree model capturing non-linear relationships.
- **XGBoost Classifier** – Gradient-boosted decision trees optimized with hyperparameter tuning.
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, ROC-AUC, and Confusion Matrix.

### 2. Time Series & Deep Learning Forecasting
- **ARIMA (Autoregressive Integrated Moving Average):** Modeled state-wise vote share trends and projected future voter turnout patterns.
- **LSTM (Long Short-Term Memory):** Recurrent Neural Network built with TensorFlow/Keras to capture sequential patterns in electoral turnout.

---

## 📂 Project Structure
```text
Task-5/
│
├── Election_Prediction_and_Forecasting.ipynb   # Main Jupyter Notebook with data analysis, modeling & visualization
├── LS_2.0.csv                                  # Lok Sabha 2019 election dataset
├── .gitignore                                  # Git ignore configuration
└── README.md                                   # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yashank08/<repo-name>.git
cd <repo-name>
```

### 2. Install Required Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost statsmodels tensorflow ipykernel
```

### 3. Run the Notebook
- **In VS Code:** Open `Election_Prediction_and_Forecasting.ipynb`, select your Python kernel, and click **Run All**.
- **In Jupyter Notebook:**
  ```bash
  jupyter notebook Election_Prediction_and_Forecasting.ipynb
  ```
- **In Google Colab:** Upload `Election_Prediction_and_Forecasting.ipynb` and `LS_2.0.csv` to Google Colab and run all cells.

---

## 📊 Dataset Information
- **Source:** Lok Sabha 2019 Election Data (`LS_2.0.csv`)
- **Key Features:** `STATE`, `CONSTITUENCY`, `NAME`, `WINNER`, `PARTY`, `GENDER`, `CRIMINAL CASES`, `AGE`, `CATEGORY`, `EDUCATION`, `ASSETS`, `LIABILITIES`, `TOTAL VOTES`, `TOTAL ELECTORS`.
