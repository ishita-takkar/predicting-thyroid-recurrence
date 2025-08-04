# 🩺 Predicting Thyroid Cancer Recurrence using Machine Learning

## 👩‍⚕️ Team Members
- Ethan Arnn  
- Krish Kankure  
- Naeem Khwajazada  
- Jiya Makhija  
- Ishita Takkar  

## 📄 Abstract
Thyroid cancer recurrence is a rare yet impactful outcome, and early identification of high-risk patients is crucial for guiding follow-up care and treatment strategies. In this project, we developed machine learning models to predict recurrence with high accuracy (target AUC > 90%) and identified clinical predictors such as cancer stage, histology, and treatment details.

Our hypothesis was that more severe disease — indicated by advanced staging or aggressive subtypes like Medullary or Anaplastic carcinoma — would correspond to higher recurrence risk.

## 🧪 Dataset
- Original dataset: `thyroid_cancer.csv`
- Selected features included:
  - Age at diagnosis
  - Histology description
  - Clinical & Pathological stage
  - Surgical and radiation treatment details
  - Demographics (sex, race)
  - Target: `recurred`

## 🔍 Exploratory Data Analysis
- Visualized distributions of clinical features
- Checked for missing data and inconsistencies
- Transformed categorical features for modeling

## 🧠 Modeling Approach
- **Algorithms Used:**
  - Logistic Regression
  - Random Forest
  - XGBoost

- **Techniques:**
  - SMOTE for class balancing (recurrence is rare)
  - Train-test split (80-20) with fixed random seed
  - ROC-AUC, Precision, Recall as key evaluation metrics

## 🏆 Results
- Achieved **>90% AUC** using XGBoost after balancing and tuning
- Key predictive features included:
  - Stage of cancer
  - Surgery and hormone treatment details
  - Histological type

## 🧰 Tools & Libraries
- Python, Jupyter Notebook  
- pandas, numpy  
- seaborn, matplotlib  
- scikit-learn, xgboost  
- imblearn (SMOTE)

## 📈 Link to Presentation
[Google Slides](https://docs.google.com/presentation/d/1agnSLcxmN5o89hOMZpi5l6CWBlaitpY5BMFBlGRN7KM/edit?usp=sharing)
