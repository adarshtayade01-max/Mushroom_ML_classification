# Mushroom Classification: Edible vs Poisonous

## Overview
This project aims to classify mushrooms as **edible** or **poisonous** using machine learning models.  
The dataset contains various morphological features such as cap shape, odor, gill size, stalk color, etc.  
Using these features, classification models are trained and evaluated to predict mushroom edibility.

---

## Problem Statement
Predict whether a mushroom is **edible** or **poisonous** based on its **morphological characteristics**.

---

## Dataset
- Source: UCI Machine Learning Repository  
- Total Samples: 8124  
- Features: 22 categorical features  
- Target Classes:
  - `e` — Edible  
  - `p` — Poisonous  

All features are encoded as single-letter categorical values.

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
  - LabelEncoder  
  - Train-Test Split  
  - Decision Tree Classifier  
  - Random Forest Classifier  

---

## Data Preprocessing
- Checked for missing values  
- Performed label encoding on all categorical features  
- Split dataset into training and testing sets  

---

## Exploratory Data Analysis (EDA)
Performed:
- Class distribution analysis  
- Visualization of key features  
- Identification of the most influential attributes
- Bivariate analysis

Findings showed that features such as **odor**, **spore print color**, and **gill size** strongly affect classification.

---

## Models Used
### Logistic Regression
- Handles categorical features well  
- Easy to interpret  
- Achieved high accuracy
  
### Decision Tree Classifier
- Handles categorical features well  
- Easy to interpret  
- Achieved high accuracy  

### Random Forest Classifier
- Ensemble technique  
- Reduces overfitting  
- Achieved high accuracy  

---

## Model Evaluation
| Model               | Train Accuracy | Test Accuracy |
|--------------------|----------------|----------------|
| Logistic Regression | 96.43%         | 95.34%
| Decision Tree       | 100%           | 100%           |
| Random Forest       | 100%           | 100%           |

*Achieving 100% accuracy is common for this dataset because of its perfectly separable nature.*

---


---

## How to Run

### 1. Clone the Repository
```bash
git clone <your-repository-link>
cd mushroom-classification

