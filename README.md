# 🚢 Titanic Survival Prediction: Machine Learning Pipeline 🧊
## 📌 Overview
This repository hosts a Machine Learning project designed to predict passenger survival on the Titanic. Using the classic Titanic dataset, the notebook builds a robust predictive model using Random Forest, complete with advanced data preprocessing pipelines and hyperparameter optimization.

## 🚀 Key Features
### ⚙️ Advanced Preprocessing:
Implements sklearn.pipeline and ColumnTransformer to handle:

### Numerical Data:
Missing value imputation and Standard Scaling.

### Categorical Data:
Imputation and One-Hot Encoding.

### 🔎 Hyperparameter Tuning:
Utilizes GridSearchCV to find the optimal parameters for the Random Forest Classifier.

### 🌲 Random Forest Model: 
Deploys an ensemble learning method for high-accuracy predictions.

### 📊 Model Evaluation: 
Detailed performance analysis using Classification Reports and Confusion Matrix heatmaps.

### 🌟 Feature Importance: 
Visualizes which factors (e.g., Fare, Age, Sex) most significantly influenced survival rates.
        
        🛠️ Tech Stack
        🐍 Python
        
        🐼 Pandas & NumPy (Data Manipulation)
        
        🧠 Scikit-Learn (Pipelines, Modeling, GridSearch)
        
        📉 Matplotlib & Seaborn (Visualization)

## 📂 Dataset
### The project uses the standard Titanic dataset (loaded via Seaborn), containing passenger details such as:

      Age, Sex, Class
      
      Fare, Embarkation Point
      
      Siblings/Spouses, Parents/Children aboard
