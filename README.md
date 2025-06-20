# Water_Quality_prediction
This is a project I worked on during my AICTE internship, where I built a machine learning model to predict whether water is safe to drink or not based on its chemical properties.
# 💧 Water Quality Prediction - AICTE Internship Project
Welcome to my machine learning project on **Water Quality Prediction**, developed as part of my **AICTE internship**. The goal of this project is to analyze various chemical properties of water and predict whether it is **potable (safe to drink)** or not.

---

## 🧠 Project Overview

In many parts of the world, access to safe drinking water is a critical issue. This project aims to apply **machine learning** to water quality data to classify samples as **potable** (1) or **not potable** (0).

Using real-world data and Python libraries, I explored, visualized, and built predictive models that help in understanding and classifying water quality.

---

## 🧪 Dataset

The dataset contains various chemical parameters of water and a target label:

| Feature              | Description                                 |
|----------------------|---------------------------------------------|
| pH                   | Acidity or alkalinity level                 |
| Hardness             | Calcium & magnesium content                 |
| Solids               | Total dissolved solids                      |
| Chloramines          | Disinfectant used in drinking water         |
| Sulfate              | Inorganic chemical in water                 |
| Conductivity         | Ionic concentration in water                |
| Organic_carbon       | Organic compounds present                   |
| Trihalomethanes      | Disinfection by-products                    |
| Turbidity            | Clarity of water                            |
| Potability (Target)  | 1 = Safe to drink, 0 = Not safe             |

---

## 🔧 Technologies Used

- **Python**
- **Pandas**, **NumPy** for data handling
- **Matplotlib**, **Seaborn** for visualization
- **Scikit-learn** for building ML models
- **Jupyter Notebook / Google Colab** for development

---

## 🔍 Workflow

1. **Data Cleaning**
   - Handled missing values using median imputation
   - Normalized and scaled features for better performance

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions
   - Checked correlations between variables
   - Identified key features impacting potability

3. **Model Building**
   - Trained and tested the following models:
     - Logistic Regression
     - Decision Tree Classifier
     - Random Forest Classifier
   - Compared accuracy, precision, recall, F1-score

4. **Model Evaluation**
   - Used confusion matrix and classification report
   - Random Forest gave the best accuracy among the models

---

## 📊 Results

- **Random Forest Classifier Accuracy:** ~79%
- **Logistic Regression Accuracy:** ~65%
- **Decision Tree Accuracy:** ~72%

Random Forest performed best due to its ensemble nature and ability to handle feature interactions.

---

## 📌 Key Learnings

- Practical experience with end-to-end ML workflow
- Importance of data preprocessing and feature scaling
- How to evaluate classification models effectively
- Real-world application of AI in environmental science

---

