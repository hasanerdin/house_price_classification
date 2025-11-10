# 🏡 House Price Classification with Supervised Learning

This project was developed as part of my **Data Science Bootcamp** at [WBS Coding School](https://www.wbscodingschool.com/).  
The main goal was to build a complete **Supervised Machine Learning pipeline** capable of predicting whether a house is **expensive or not** — a **binary classification** task.

---

## 📊 Project Overview

We used a dataset containing multiple **house features** (size, number of rooms, location, age, etc.)  
The workflow includes **data preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation**, all implemented using **scikit-learn Pipelines** for full automation and reproducibility.

---

## 🧩 Techniques and Tools

### 🔹 Libraries
- **Python**
- **Pandas**, **NumPy** – data manipulation and transformation  
- **Matplotlib**, **Seaborn** – exploratory data analysis (EDA) and visualization  
- **scikit-learn** – model training, pipelines, and evaluation  

### 🔹 Machine Learning Models
- **Decision Tree Classifier**  
- **Random Forest Classifier**  
- **K-Nearest Neighbors (KNN)**  
- **Logistic Regression**  
- **Support Vector Machine (SVM)**  

### 🔹 Key Techniques
- **Pipeline & ColumnTransformer**
  - Processed **Numerical**, **Ordinal**, and **Categorical** features in **parallel pipelines**
  - Applied appropriate transformations:
    - Scaling numerical columns  
    - Encoding categorical and ordinal features  
  - Ensured full automation from preprocessing to prediction

- **GridSearchCV** for hyperparameter optimization  
- **Model Evaluation** using multiple metrics  
- **Feature Importance** analysis for interpretability  

---

## ⚙️ Workflow

### 1️⃣ Data Preprocessing
- Handled missing values and duplicates  
- Detected and treated outliers  
- Encoded categorical and ordinal variables  
- Scaled numerical features  

### 2️⃣ Automated Pipelines
- Implemented **scikit-learn Pipelines** to structure the preprocessing and modeling steps  
- Used **ColumnTransformer** to handle multiple feature types simultaneously  
- Ensured seamless integration of preprocessing → training → prediction steps  

### 3️⃣ Model Training and Optimization
- Trained multiple classification models  
- Used **GridSearchCV** to determine best hyperparameters  
- Evaluated each model based on:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-Score**

### 4️⃣ Evaluation and Interpretation
- Generated **Confusion Matrices** for each model  
- Visualized performance metrics using **bar charts and heatmaps**  
- Analyzed **Feature Importance** for tree-based algorithms  

---

## 🏁 Results

After tuning and evaluation:
- Models were compared across all key metrics.  
- The final **best-performing model** was selected based on a balanced trade-off between **Precision**, **Recall**, and **F1-Score**.  
- Visualizations clearly highlighted differences between models and key contributing features.

