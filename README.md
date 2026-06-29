# ✈️ Airline Flight Delay Prediction using Machine Learning

## 📌 Overview

Airline delays significantly impact passengers, airlines, and airport operations. This project develops a Machine Learning model to predict whether a flight is likely to experience a high delay using historical airline performance data.

The project follows a complete Data Science workflow including:

- Data Collection
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Model Development
- Model Evaluation
- Interactive Power BI Dashboard

---

## 🚀 Features

- Comprehensive data preprocessing pipeline
- Missing value handling and outlier removal
- Feature engineering for delay prediction
- Exploratory Data Analysis with visualizations
- Logistic Regression and Random Forest models
- Model evaluation using multiple metrics
- Interactive Power BI dashboard
- Well-structured Jupyter notebooks

---

## 📂 Project Structure

```
Airline_Flight_Delay_Prediction/
│
├── dataset/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   ├── 01_data_loading.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda.ipynb
│   ├── 04_model_building.ipynb
│   ├── 05_powerbi_preparation.ipynb
│
├── reports/
│   ├── figures/
│   ├── model_predictions.csv
│
├── models/
│   └── (ignored from GitHub)
│
├── airline flight delay 1st dashboard.pbix
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📊 Dataset

**Source**

U.S. Bureau of Transportation Statistics (BTS)

https://www.transtats.bts.gov/

### Dataset Information

- Flight records from **2021 – July 2025**
- More than **102,000 records**
- 25+ features
- Airline performance
- Airport information
- Delay statistics
- Cancellation information
- Weather-related delays

---

## 🛠 Technologies Used

### Programming

- Python 3.x

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

### Visualization

- Power BI

### Development Environment

- Jupyter Notebook

---

## 📈 Machine Learning Workflow

### 1. Data Preprocessing

- Missing value imputation
- Duplicate removal
- Outlier handling
- Label Encoding
- Feature Scaling

---

### 2. Feature Engineering

Created additional features such as:

- Delay Rate
- Cancellation Rate
- Diversion Rate
- Total Delay Minutes
- High Delay Label

---

### 3. Models Used

- Logistic Regression
- Random Forest Classifier

---

## 📊 Model Performance

| Model | Accuracy | ROC-AUC |
|--------|----------|----------|
| Logistic Regression | **98.15%** | **0.9993** |
| Random Forest | **97.17%** | **0.9971** |

Random Forest was selected as the final model due to its robustness and feature importance analysis.

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

---

## 📈 Power BI Dashboard

The project includes an interactive Power BI dashboard showing:

- Airline Performance
- Airport Performance
- Monthly Delay Trends
- Delay Cause Analysis
- Airport Busyness
- Delay Rate Heatmaps
- Prediction Results
- Interactive Filters

---

## 💡 Key Insights

- Summer months experience the highest delays.
- Weather and late aircraft are major causes of delays.
- Airport congestion significantly affects on-time performance.
- Certain airlines consistently perform better than others.
- Departure timing strongly influences delay probability.

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/kushalgowda15/Airline-Flight-Delay-Prediction.git
```

### Navigate to the project

```bash
cd Airline-Flight-Delay-Prediction
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Run the notebooks in order:

1. Data Loading
2. Data Cleaning
3. EDA
4. Model Building
5. Power BI Preparation

---

## 📌 Future Improvements

- Deep Learning models
- XGBoost and LightGBM
- Real-time weather API integration
- Flight Tracking API
- Streamlit Web Application
- Docker Deployment
- Cloud Deployment (AWS/Azure)

---

## 📸 Dashboard Preview

> <img width="451" height="254" alt="image" src="https://github.com/user-attachments/assets/17915e90-ec85-4898-bf26-ba7d8d75a150" />
<img width="450" height="251" alt="image" src="https://github.com/user-attachments/assets/f6027dc5-4469-416f-b119-e05b7975a546" />



Example:

```
reports/figures/dashboard.png
```

---

## 📄 License

This project is intended for educational and research purposes.

---

## 👨‍💻 Author

**Kushal Gowda**

GitHub: https://github.com/kushalgowda15

