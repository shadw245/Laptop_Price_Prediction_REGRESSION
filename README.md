# 💻 Laptop Price Prediction Using Machine Learning

A machine learning regression project that predicts laptop prices based on their hardware specifications. The project follows an end-to-end machine learning pipeline, including data preprocessing, feature engineering, exploratory data analysis (EDA), model training, hyperparameter tuning, model evaluation, and prediction generation.

---

# 📌 Project Overview

Laptop prices are influenced by multiple hardware and software specifications such as processor, RAM, storage, graphics card, operating system, and display characteristics. The goal of this project is to build a regression model capable of accurately estimating a laptop's price based on these features.

The project demonstrates a complete machine learning workflow using Python and Scikit-learn, with an emphasis on data preprocessing, feature engineering, model comparison, and performance optimization.

---

# 🚀 Features

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Categorical feature encoding
* Pipeline-based preprocessing
* Cross-validation
* Multiple regression models
* Hyperparameter tuning using GridSearchCV and RandomizedSearchCV
* Learning curve analysis
* Overfitting detection
* Final prediction generation for unseen test data

---

# 📂 Dataset

The project uses separate training and testing datasets containing laptop specifications.

### Features include:

* Company
* Product Type
* CPU
* GPU
* RAM
* Storage
* Operating System
* Screen Resolution
* Screen Size
* Weight
* Additional engineered features

**Target Variable**

* **Price (Euro)**

---

# ⚙️ Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

# 🔍 Exploratory Data Analysis

The notebook performs exploratory data analysis to better understand the dataset before model training.

The analysis includes:

* Dataset overview
* Missing value inspection
* Distribution analysis
* Correlation analysis
* Numerical feature visualization
* Categorical feature visualization
* Post-preprocessing EDA
* Feature distribution after engineering

Generated visualizations are automatically saved inside the **outputs/eda** directory.

---

# 🧹 Data Preprocessing

Several preprocessing techniques were applied before training the models:

* Duplicate removal
* Missing value handling
* Feature engineering
* Numerical feature scaling
* Categorical feature encoding
* ColumnTransformer pipelines
* Train-validation split

The preprocessing pipeline ensures that all transformations are consistently applied during both training and prediction.

---

# 🤖 Machine Learning Models

The project evaluates multiple regression algorithms before selecting the best-performing model.

Models include:

* Ridge Regression
* Decision Tree Regressor
* Linear Regression
* Lasso Regression
* Polynomial Degree 3

The models are evaluated using cross-validation to ensure reliable performance estimates.

---

# 🎯 Hyperparameter Tuning

Model performance is improved through hyperparameter optimization using:

* **GridSearchCV**
* **RandomizedSearchCV**

The tuned models are compared to identify the optimal configuration.

---

# 📈 Model Evaluation

The regression models are evaluated using:

* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)
* R² Score

Additional evaluation techniques include:

* 5-Fold Cross Validation
* Learning Curves
* Overfitting Analysis (Training vs Validation Performance)

---

# 📁 Project Structure

```
Laptop-Price-Prediction/

│── data/
│   ├── train_data.csv
│   └── test_data.csv
│
│── laptop_price_project.ipynb
│── submission.csv
└──  README.md
```

---

# 📊 Results

The project compares multiple regression models and selects the best-performing model after hyperparameter tuning. The final model is trained on the processed dataset and used to generate predictions for unseen laptop data.

The notebook also includes:

* Cross-validation results
* Learning curve visualization
* Overfitting analysis
* Final prediction generation (`submission.csv`)

---


