# Heart Disease Risk Prediction Using Machine Learning

## Project Overview

This project focuses on predicting the risk of heart disease using machine learning techniques based on healthcare and lifestyle-related factors. The system analyzes patient information such as BMI, cholesterol level, blood pressure, smoking habits, stress level, sleep duration, and physical activity to classify individuals into low-risk or high-risk categories.

In addition to prediction, the project also provides personalized lifestyle recommendations and visual healthcare insights using Power BI dashboards. The main objective of this project is to support preventive healthcare and increase awareness about factors that contribute to cardiovascular diseases.

---

# Features

* Healthcare dataset preprocessing
* Exploratory Data Analysis (EDA)
* Multiple machine learning models
* Heart disease risk prediction
* Personalized recommendation system
* Power BI dashboard visualization
* Model evaluation and comparison

---

# Technologies Used

## Programming Language

* Python

## Development Tools

* Jupyter Notebook
* Google Colab
* Power BI
* GitHub

## Python Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

---

# Dataset Features

The dataset contains healthcare and lifestyle-related attributes including:

* Age
* Gender
* BMI
* Blood Pressure
* Cholesterol Levels
* Smoking Status
* Alcohol Consumption
* Physical Activity Level
* Stress Level
* Sleep Hours
* Family History
* Heart Disease Risk (Target Variable)

---

# Project Workflow

## 1. Dataset Collection

Healthcare and lifestyle datasets were collected and stored in CSV format for analysis and prediction.

## 2. Data Preprocessing

The preprocessing stage included:

* Handling missing values
* Removing duplicate records
* Encoding categorical variables
* Feature scaling using StandardScaler

## 3. Exploratory Data Analysis (EDA)

EDA was performed to understand patterns and relationships within the dataset using:

* Histograms
* Heatmaps
* Correlation analysis
* Scatter plots
* Box plots

## 4. Feature Selection

Important healthcare attributes influencing heart disease risk were selected to improve model performance and reduce complexity.

## 5. Machine Learning Model Training

The following machine learning algorithms were implemented and compared:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* XGBoost

## 6. Prediction System

The trained models were used to predict whether an individual falls into:

* Low Risk
* High Risk

## 7. Recommendation System

A recommendation system was developed to provide personalized health suggestions based on prediction results and health indicators.

Example recommendations include:

* Reducing smoking and alcohol consumption
* Improving sleep quality
* Increasing physical activity
* Managing stress levels
* Maintaining a healthy BMI

## 8. Dashboard Visualization

Power BI dashboards were created to visualize healthcare insights such as:

* BMI analysis
* Cholesterol trends
* Stress level analysis
* Smoking statistics
* Gender-based risk comparison

---

# Model Performance

| Algorithm           | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 84%      |
| Decision Tree       | 86%      |
| SVM                 | 88%      |
| Random Forest       | 92%      |
| XGBoost             | 93%      |

Among all models, XGBoost achieved the highest prediction accuracy for the given healthcare dataset.

---

# Evaluation Metrics

The models were evaluated using multiple performance metrics including:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC Score
* Confusion Matrix

These metrics helped measure the effectiveness and reliability of the prediction system.

---

# Recommendation System

The recommendation module generates preventive healthcare suggestions based on:

* Predicted heart disease risk
* Lifestyle factors
* Health indicators

For example, if a user has high cholesterol, obesity, smoking habits, or high stress levels, the system recommends lifestyle improvements such as regular exercise, stress management, improved diet, and better sleep habits.

---

# Ethical and Security Considerations

Since the project deals with healthcare-related information, data privacy and responsible usage are important considerations. The system is intended for educational and analytical purposes only and should not replace professional medical diagnosis or consultation.

---

# Challenges Faced

Some of the challenges encountered during the project include:

* Missing values in the dataset
* Imbalanced healthcare data
* Overfitting issues in machine learning models
* Feature selection complexity
* Dashboard optimization for large datasets

These challenges were addressed using preprocessing techniques, feature scaling, and model optimization methods.

---

# Future Enhancements

Possible future improvements for the project include:

* Real-time health monitoring
* IoT device integration
* Mobile application development
* Cloud-based deployment
* Deep learning implementation
* Personalized diet and fitness recommendations

---

# How to Run the Project

## Clone the Repository

```bash id="zb4r91"
git clone <your-github-repository-link>
```

## Install Required Libraries

```bash id="h2ngpi"
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

## Run the Jupyter Notebook

```bash id="gbjlwm"
jupyter notebook
```

Open the notebook and run all cells sequentially.

---

# Project Outcome

The project demonstrates how machine learning and healthcare analytics can be combined to predict heart disease risk and generate personalized health recommendations. It also highlights the importance of preventive healthcare and data-driven decision-making in healthcare systems.

---

