# Predicting survival in the ICU

- This aim of the attached notebook is to develop and optimise 3 machine learning models (logistic regression, decision tree and random forest) to predict the survival of patients in the ICU
- There are 3 files in this repository 
    - `ICU.csv` is the dataset used in the project. This was taken from https://www.kaggle.com/datasets/ukveteran/icu-patients
    - `icu.db` is the SQLlite3 database containing data from the csv file
    - `Predict_Survival_ICU_Patients.ipynb` is the Jupyter notebook presenting the development and evaluation of models
- There are 5 parts to the jupyter notebook
    1. Convert data to tidy format
    2. Export normalised tables to an SQLite3 database
    3. Visualisations
    4. Developing and evaluating models
    5. Summary of findings
