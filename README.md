# Airline Passenger Satisfaction Prediction



A machine learning project that predicts airline passenger satisfaction using passenger and flight-related information.



## Project Overview



This project explores and develops machine learning models to predict whether airline passengers are satisfied or dissatisfied with their flight experience.



## Dataset



The dataset comes from the Airline Passenger Satisfaction Kaggle competition.



Dataset files are not included in this repository. Please refer to the original Kaggle competition for access and usage conditions.



## Methods



- Exploratory Data Analysis (EDA)

- Missing value imputation

- Numerical feature scaling

- Categorical feature encoding

- Logistic Regression

- Hyperparameter tuning using GridSearchCV

- 5-fold cross-validation



## Model Performance



*\*Model:\*\* Logistic Regression



*\*Best parameter:\*\* C = 0.01



*\*Cross-validation ROC-AUC:\*\* 0.92187



*\*Validation ROC-AUC:\*\* 0.92046

## Reproducibility

This project was developed using **Google Colab** with Python and Scikit-learn.

- **Environment:** Google Colab
- **Dataset:** [Airline Passenger Satisfaction – Kaggle Competition](https://www.kaggle.com/competitions/airline-passenger-satisfaction)
- **Model:** Logistic Regression
- **Preprocessing:** SimpleImputer, StandardScaler, and OneHotEncoder
- **Hyperparameter tuning:** 5-fold GridSearchCV
- **Evaluation metric:** ROC-AUC

To reproduce the results, download the competition dataset from Kaggle and run the notebook in Google Colab.

## Technologies



- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Scikit-learn

- Google Colab



## Repository Structure



```text

airline-passenger-satisfaction/

├── README.md

├── LICENSE

├── .gitignore

├── requirements.txt

└── notebooks/

&#x20;   └── airline\_passenger\_satisfaction.ipynb

```



## Author



Aw Tha Da



## License



This project is licensed under the MIT License.

