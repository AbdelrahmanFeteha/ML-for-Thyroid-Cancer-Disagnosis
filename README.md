# Thyroid Tumor Classification using Machine Learning
This project focuses on classifying thyroid tumors as benign or malignant based on demographic, clinical, and lifestyle data. It was developed as part of CMP 466 (Machine Learning and Data Mining) at the American University of Sharjah.

## Dataset
- Source: [Kaggle - Thyroid Cancer Risk Dataset](https://www.kaggle.com/datasets/bhargavchirumamilla/thyroid-cancer-risk-dataset)
- Features include age, gender, TSH, T3, T4 levels, nodule size, smoking status, alcohol consumption, and the diagnosis label (benign or malignant).

## Models Used
- Logistic Regression (with class weighting)
- Decision Tree
- Support Vector Machine (Linear and RBF)
- XGBoost
- Naive Bayes
- K-Nearest Neighbors

## Methodology
- Data preprocessing and normalization
- Handling class imbalance using SMOTE, undersampling, and class weights
- Feature selection using correlation analysis and ANOVA F-test
- Evaluation metrics: recall, F1-score, AUC-ROC
- Hyperparameter tuning using GridSearchCV

## Results
Among the tested models, the Linear SVM achieved the highest recall (0.77) for malignant cases, making it the most effective model for correctly identifying potentially harmful tumors.

## Notebook
- [Open in Google Colab][(https://colab.research.google.com/drive/1HxNBcuE-Z0WGvfazO_tlZiwFZbsaLjVF?usp=sharin](https://colab.research.google.com/drive/1HxNBcuE-Z0WGvfazO_tlZiwFZbsaLjVF?usp=sharing)g)
