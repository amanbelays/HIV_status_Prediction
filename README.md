# Predicting HIV Status Using Machine Learning
This repository contains my internship project at the Ethiopian Public Health Institute (EPHI) - National Data Management Center (NDMC). The project explores machine learning (ML) approaches to predict HIV status based on demographic, behavioural, and socioeconomic factors from the Ethiopian HIV Impact Assessment (EPHIA) survey.

## 🔍 Project Overview
The goal of this project is to leverage ML techniques to improve HIV status prediction accuracy, providing valuable insights into Ethiopia’s HIV epidemic, particularly in urban areas.

### 📌 Key Objectives
- Utilize ML models to predict HIV status.
- Handle challenges such as imbalanced data and missing values.
- Compare different ML models and optimize performance.
- Provide insights into the public health implications of HIV prediction.

## 📊 Dataset
- **Source:** Ethiopian Population-based HIV Impact Assessment (EPHIA) (2017-2018)
- **Size:** 11,810 observations and 312 variables
- **Features Used:** 11 independent variables selected through literature review
- **Target Variable:** HIV status (positive/negative)

## ⚙️ Methods & Tools
- **Data Preprocessing:** Handling missing values, feature engineering, standardization
- **Machine Learning Models:** 
  - Logistic Regression
  - Decision Trees
  - Random Forest (Final Model)
  - Gradient Boosting
- **Techniques Applied:** 
  - SMOTE for handling imbalanced data
  - Hyperparameter tuning (cross-validation)
  - Performance evaluation (AUC-ROC, F1-score, accuracy)
- **Libraries Used:**
  -'tidyverse', 'skimr', 'GGally', 'tidymodels','usemodels', 'VIP, 'themis' 
## 📈 Results
- The **Random Forest model** demonstrated the best performance.
- Evaluation metrics:
  - Accuracy: **96.5%**
  - ROC-AUC: **0.78**
  - Sensitivity: **99.1%**
  - Specificity: **6.2%**
- Feature importance analysis revealed the following key predictors of HIV status.

- ![image](https://github.com/user-attachments/assets/7f9c81f3-5645-4a87-bb48-87b1391a3c61)

## 📌 Challenges Faced
- Limited domain expertise required extensive literature review.
- High-dimensional dataset with missing values.
- An imbalanced dataset requires advanced techniques (SMOTE).
- Sensitivity-specificity trade-off in model optimization.
## 📢 Lessons Learned
- Handling real-world health data challenges.
- Importance of feature selection and engineering.
- Applying ML techniques to public health research.
