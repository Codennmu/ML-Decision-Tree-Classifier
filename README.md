# Heart Disease Classification with Decision Trees

## Overview

This project presents a complete Machine Learning pipeline for Heart Disease Classification using the Decision Tree algorithm. The notebook demonstrates data preprocessing, exploratory data analysis (EDA), feature selection, dimensionality reduction, model training, pruning, evaluation, and prediction on new patient samples.

The project is implemented using Python, Scikit-learn, Pandas, NumPy, and Matplotlib within a Jupyter Notebook environment.

---

# Project Objectives

* Perform Exploratory Data Analysis (EDA)
* Analyze feature distributions and correlations
* Apply feature selection techniques
* Train Decision Tree Classifier
* Compare Full Tree vs Pruned Tree
* Evaluate classification performance
* Predict heart disease for new patients

---

# Dataset Information

The dataset contains clinical attributes related to heart disease diagnosis.

### Features Used

| Feature  | Description                 |
| -------- | --------------------------- |
| age      | Age of patient              |
| sex      | Gender                      |
| cp       | Chest pain type             |
| trestbps | Resting blood pressure      |
| chol     | Serum cholesterol           |
| fbs      | Fasting blood sugar         |
| restecg  | Resting ECG results         |
| thalach  | Maximum heart rate achieved |
| exang    | Exercise induced angina     |
| oldpeak  | ST depression               |
| slope    | Slope of ST segment         |
| ca       | Number of major vessels     |
| thal     | Thalassemia                 |
| target   | Heart disease presence      |

---

# Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

# Repository Structure

```bash
Decision-Tree-Classification/
│
├── Classification_with_Decision_Trees.ipynb
├── requirements.txt
└── README.md
```

---

# Exploratory Data Analysis (EDA)

The notebook includes:

* Basic statistical analysis
* Missing value analysis
* Class distribution visualization
* Feature distribution analysis
* Correlation heatmap

## Correlation Heatmap
<img width="1204" height="887" alt="corelation heatmap" src="https://github.com/user-attachments/assets/26f969a5-cf05-4650-b340-03a3c4f3f8bd" />

---

# Feature Selection Methods

The following feature selection techniques are implemented:

1. Pearson Correlation
2. Mutual Information
3. Decision Tree Feature Importance

A combined ranking table is generated to identify the most important features.

---

# PCA (Principal Component Analysis)

The project applies PCA after standardization to reduce dimensionality and visualize feature relationships.

---

# Decision Tree Classification

The notebook implements:

* Full Decision Tree
* Tree Visualization
* Tree Pruning
* Optimal Depth Selection
* Accuracy Comparison

## Full Decision Tree

<img width="2387" height="987" alt="full decision tree" src="https://github.com/user-attachments/assets/7b67645f-3140-479f-9e04-313943841828" />

---

# Model Evaluation

The following evaluation metrics are used:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Precision
* Recall
* F1-Score

## Confusion Matrix

<img width="1338" height="493" alt="confusion" src="https://github.com/user-attachments/assets/a366448b-d837-4380-b493-ba97a2b57bea" />

---

# Model Comparison

The notebook compares multiple Decision Tree configurations using:

* Accuracy
* Tree Depth
* Model Complexity
* Classification Performance

---

# Prediction on New Patients

The trained model is used to predict heart disease risk for new patient samples.

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Decision-Tree-Classification.git
```

Move into the project directory:

```bash
cd Decision-Tree-Classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# Running the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
Classification_with_Decision_Trees.ipynb
```

---

# Requirements

The project dependencies are listed in:

```bash
requirements.txt
```

---

# Results

The project successfully demonstrates:

* End-to-end ML workflow
* Feature importance analysis
* Decision Tree optimization
* Pruning techniques
* Clinical data classification
* Model evaluation and interpretation

---

# Future Improvements

* Random Forest implementation
* XGBoost comparison
* Hyperparameter tuning
* Cross-validation
* Streamlit deployment
* Real-time prediction system

---

# Author

Saad Mazhar Khan

---

# License

This project is licensed under the MIT License.
