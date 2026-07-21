# CodeAlpha-Task2
Heart Disease Prediction
# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals identify patients who are at high risk and enable timely medical intervention.

This project develops a machine learning model to predict the presence of heart disease using patient clinical data. Multiple machine learning classification algorithms were trained, evaluated, and compared to identify the best-performing model.

---

# 🎯 Objectives

- Predict whether a patient has heart disease using clinical attributes.
- Perform data preprocessing and exploratory data analysis (EDA).
- Train multiple machine learning classification models.
- Compare model performance using different evaluation metrics.
- Select the best-performing model for heart disease prediction.

---

# 📂 Dataset

**Dataset Name:** Heart Disease Dataset (Cleveland)

**Source:** UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/45/heart+disease

### Dataset Information

- Original Records: 303
- Records Used After Data Cleaning: **219**
- Training Samples: **175**
- Testing Samples: **44**
- Number of Features Used: **13**
- Train-Test Split: **80:20**

---

# 📋 Features

The following medical attributes were used as input features:

| Feature | Description |
|----------|-------------|
| age | Age of patient |
| sex | Gender |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol |
| fbs | Fasting blood sugar |
| restecg | Resting ECG results |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of peak exercise ST segment |
| ca | Number of major vessels |
| thal | Thalassemia |

### Target Variable

- **0** → No Heart Disease
- **1** → Heart Disease

---

# 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib

---

# 📊 Project Workflow

## 1. Data Collection

- Loaded Heart Disease dataset
- Explored dataset structure

---

## 2. Data Preprocessing

The following preprocessing steps were performed:

- Checked dataset information
- Handled missing values
- Removed incomplete records
- Checked duplicate records
- Converted data types
- Created target variable
- Selected relevant features
- Standardized numerical features using StandardScaler
- Split data into training and testing datasets

Training Data Shape

```
(175, 13)
```

Testing Data Shape

```
(44, 13)
```

---

## 3. Exploratory Data Analysis (EDA)

Performed exploratory analysis using:

- Dataset overview
- Missing value analysis
- Correlation Heatmap
- Histograms
- Box Plots
- Count Plots
- Feature Distribution
- Class Distribution

---

## 4. Machine Learning Models

The following supervised classification algorithms were implemented:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gradient Boosting
- AdaBoost
- XGBoost

---

## 5. Model Evaluation

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

---

# 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|--------|---------:|----------:|--------:|---------:|---------:|
| AdaBoost | **81.82%** | **66.67%** | **54.55%** | **60.00%** | **81.82%** |
| K-Nearest Neighbors (KNN) | 79.55% | 60.00% | 54.55% | 57.14% | 81.96% |
| Random Forest | 79.55% | 75.00% | 27.27% | 40.00% | 85.95% |
| Logistic Regression | 77.27% | 55.56% | 45.45% | 50.00% | 77.14% |
| XGBoost | 77.27% | 55.56% | 45.45% | 50.00% | 77.96% |
| Gradient Boosting | 77.27% | 55.56% | 45.45% | 50.00% | 81.54% |
| Support Vector Machine (SVM) | 75.00% | 50.00% | 18.18% | 26.67% | 79.34% |
| Decision Tree | 72.73% | 44.44% | 36.36% | 40.00% | 60.61% |

---

# 🏆 Best Performing Model

## AdaBoost Classifier

The AdaBoost Classifier achieved the best overall performance among all the machine learning models.

### Performance Metrics

- Accuracy: **81.82%**
- Precision: **66.67%**
- Recall: **54.55%**
- F1-Score: **60.00%**
- ROC-AUC Score: **81.82%**

Based on these evaluation metrics, AdaBoost was selected as the final prediction model.

---

# 📊 Visualizations Included

The project contains the following visualizations:

- Correlation Heatmap
- Histograms
- Box Plots
- Count Plots
- Class Distribution
- Confusion Matrix
- ROC Curve
- Model Comparison Charts

---

# 📁 Project Structure

```
Heart-Disease-Prediction/
│
├── Heart_Disease_Prediction.ipynb
├── heart.csv
├── README.md
├── requirements.txt
├── best_model.pkl
├── scaler.pkl
└── images/
```

---

# 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/Heart-Disease-Prediction.git
```

### Navigate to Project

```bash
cd Heart-Disease-Prediction
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Heart_Disease_Prediction.ipynb
```

Run all notebook cells sequentially.

---

# 📦 Required Libraries

```
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
joblib
```

---

# 📌 Results

- Successfully preprocessed the Heart Disease dataset.
- Performed Exploratory Data Analysis (EDA).
- Trained and evaluated eight machine learning classification algorithms.
- Compared models using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
- AdaBoost achieved the highest overall accuracy of **81.82%**.
- Generated Confusion Matrix and Classification Report for the best-performing model.
- Selected AdaBoost as the final prediction model based on comparative performance.

---

# 🎯 Conclusion

This project demonstrates the application of supervised machine learning techniques for heart disease prediction using structured clinical data. Multiple classification algorithms were compared to identify the most suitable predictive model.

Among all evaluated models, the **AdaBoost Classifier** achieved the best overall performance with an **accuracy of 81.82%**, making it the selected model for this project.

The results highlight the effectiveness of ensemble learning techniques for medical prediction tasks and demonstrate the importance of comparing multiple algorithms before selecting a final model.

---

# 🔮 Future Scope

The project can be further enhanced by:

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Feature importance analysis
- Explainable AI (SHAP)
- Streamlit web application
- Flask/FastAPI deployment
- Integration with real-time healthcare systems

---



# 📄 License

This project is intended for educational and academic purposes.
