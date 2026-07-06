# 🚢 Titanic Survival Prediction using Gradient Boosting with Hyperparameter Tuning

A Machine Learning classification project that predicts passenger survival on the **Titanic dataset** using the **Gradient Boosting Classifier**. This project demonstrates how different **hyperparameter tuning techniques** improve model performance by comparing the results of **GridSearchCV**, **RandomizedSearchCV**, and **Optuna**.

The project provides a practical understanding of ensemble learning, model optimization, and performance evaluation.

---

## 📌 Project Overview

Gradient Boosting is a powerful ensemble learning algorithm that builds multiple decision trees sequentially, where each new tree attempts to correct the errors made by the previous trees.

This project begins with a baseline Gradient Boosting model and then improves its performance using three popular hyperparameter optimization techniques.

The workflow includes:

- Data Loading
- Data Preprocessing
- Feature Selection
- Train-Test Split
- Gradient Boosting Classification
- Hyperparameter Tuning
- Model Evaluation
- Performance Comparison

---

## 🎯 Objectives

- Predict Titanic passenger survival.
- Build a baseline Gradient Boosting Classifier.
- Improve model performance using hyperparameter tuning.
- Compare different optimization techniques.
- Understand ensemble learning concepts.
- Evaluate classification models using multiple metrics.

---

## 📂 Dataset

This project uses the **Titanic Dataset**, which contains passenger information such as:

- Passenger Class (Pclass)
- Sex
- Age
- Fare
- Number of Siblings/Spouses
- Number of Parents/Children
- Embarked Port
- Target Variable (Survived)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Optuna
- Matplotlib
- Jupyter Notebook

---

## 📚 Machine Learning Concepts

- Supervised Learning
- Classification
- Ensemble Learning
- Gradient Boosting Classifier
- Hyperparameter Tuning
- GridSearchCV
- RandomizedSearchCV
- Optuna Optimization
- Train-Test Split
- Model Evaluation

---

## 🔄 Project Workflow

```text
Load Titanic Dataset
        │
        ▼
Data Preprocessing
        │
        ▼
Feature Selection
        │
        ▼
Train-Test Split
        │
        ▼
Baseline Gradient Boosting Model
        │
        ▼
Hyperparameter Tuning
   ├──────────────┐
   │              │
GridSearchCV  RandomizedSearchCV
   │              │
   └──────┬───────┘
          │
       Optuna
          │
          ▼
Model Evaluation
          │
          ▼
Performance Comparison
```

---

## 📊 Model Performance

| Model | Test Accuracy |
|--------|--------------:|
| Baseline Gradient Boosting | Baseline Model |
| GridSearchCV | **80.45%** |
| RandomizedSearchCV | **81.56%** |
| Optuna | **83.24%** ⭐ |

**Best Performing Model:** Optuna Hyperparameter Optimization

---

## 📁 Repository Structure

```text
Gradient-Boosting-Hyperparameter-Tuning/
│
├── Hyperparameter_Tuning_Gradient_Boosting_Algorithm.ipynb
├── train.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Hyperparameter Tuning Techniques

### 🔹 GridSearchCV

- Searches every possible parameter combination.
- Finds the optimal parameter set.
- Computationally expensive.

---

### 🔹 RandomizedSearchCV

- Randomly samples parameter combinations.
- Faster than GridSearchCV.
- Produces competitive results with lower computation time.

---

### 🔹 Optuna

- Modern optimization framework.
- Uses intelligent search strategies.
- Faster convergence.
- Achieved the highest accuracy in this project.

---

## 📈 Model Evaluation

The models are evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

---

## 💡 Key Features

- End-to-end machine learning classification project
- Gradient Boosting Classifier implementation
- Baseline vs tuned model comparison
- Three hyperparameter tuning techniques
- Performance evaluation using classification metrics
- Clean and beginner-friendly implementation
- Real-world Titanic dataset

---

## 🚀 Future Improvements

- XGBoost Classifier
- LightGBM
- CatBoost
- Bayesian Optimization
- Feature Engineering
- Cross Validation
- ROC Curve & AUC
- SHAP Explainability
- Streamlit Web Application

---

## 📖 Learning Outcomes

This project helped strengthen my understanding of:

- Ensemble Learning
- Gradient Boosting Algorithm
- Hyperparameter Optimization
- GridSearchCV
- RandomizedSearchCV
- Optuna
- Classification Metrics
- Model Evaluation
- Performance Comparison
- Machine Learning Optimization Techniques

---

## ⭐ Why This Project?

This project demonstrates not only how to build a powerful **Gradient Boosting Classifier** but also how different hyperparameter tuning techniques can significantly improve model performance. By comparing **GridSearchCV**, **RandomizedSearchCV**, and **Optuna**, the project provides practical experience in machine learning optimization and model selection.

---

## 👨‍💻 Author

**Prince Maheta**

**Aspiring Data Scientist | Machine Learning | Data Analytics | Python**

---

## ⭐ Support

If you found this project useful, please consider giving this repository a ⭐ on GitHub. Your support motivates me to build and share more Machine Learning and Data Science projects.
