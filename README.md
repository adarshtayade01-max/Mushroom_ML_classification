# Mushroom Classification: Edible vs Poisonous

## Overview
This project aims to classify mushrooms as **edible** or **poisonous** using machine learning models.  
The dataset contains various morphological features like cap shape, odor, gill size, stalk color, etc.  
Using these features, classification models are trained and evaluated to predict mushroom edibility.




---

## Problem Statement
Predict whether a mushroom is **edible** or **poisonous** based on its **morphological features**.

<img width="900" height="1350" alt="image" src="https://github.com/user-attachments/assets/d1faff5c-0a0d-4ea3-a43e-53081dc4f1f5" />


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
  - Logistic Regression
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
- Works well for classification tasks  
- Needs encoded numerical features  
- Gave lower accuracy compared to tree-based models
  
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
| Model               |  Accuracy     |     Recall     |  Precision   |   F1 score    | 
|--------------------|----------------|----------------|--------------|---------------|
| Logistic Regression | 96.43%         |   97.31%      |  95.36%      |   96.32%      |
| Decision Tree       | 100%           |   100%        |  100%        |   100%        |
| Random Forest       | 100%           |   100%        |  100%        |   100%        |

*Achieving 100% accuracy is common for this dataset because of its perfectly separable nature.*

---




## Future Work


- Experiment with SVM, XGBoost, or Gradient Boosting

- Build a Streamlit or Flask web application

- Deploy the model online for real-time predictions


## Conclusion

This project demonstrates that mushroom edibility can be accurately predicted using morphological features.
Tree-based models like Decision Tree and Random Forest achieved perfect accuracy on this dataset.

