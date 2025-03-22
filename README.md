# Heart Disease Prediction

This project uses various machine learning models to predict whether a patient has heart disease based on a dataset of medical features. The project tests different classification models and evaluates their performance to identify the most effective algorithm for predicting heart disease.

Best Model: Random Forest with 98% accuracy score and 98% recall score.

Dataset: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

# Features
- Models:
  - Random Forest
  - GaussianNB
  - Gradient Boosting
  - KNeighbors
  - Logistic Regression
  - SVC
- Scoring acurracy of each model
- Hyperparameter Tuning
- Feature Importances

# Requirements
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib (for visualizations)
- Seaborn (for statistical plots)

# Installation

```
git clone https://github.com/MechamJonathan/heart_disease_prediction.git
cd heart_disease_prediction
pip3 install pandas numpy scikit-learn matplotlib seaborn
```

# Running on New data
run the following in notebook
```
best_rf.predict({New formated data})
```

  
