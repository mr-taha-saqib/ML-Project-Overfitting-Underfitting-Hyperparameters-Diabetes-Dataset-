# Machine Learning Project: Overfitting, Underfitting, and Hyperparameters

This project explores regression models, specifically focusing on overfitting, underfitting, and hyperparameter tuning. The primary task is to build and compare different linear models to predict diabetes progression using the well-known Diabetes dataset.  

We first implement a linear regression model using an analytical solution (without regularization), followed by a Lasso regression model, which adds L1 regularization. Finally, we experiment with different levels of regularization and analyze the performance of the models in terms of prediction accuracy, overfitting, and underfitting.

---

We use the Diabetes dataset from **scikit-learn**, which contains **442 samples** and **10 features** representing different baseline variables like BMI, blood pressure, etc., for predicting the progression of diabetes one year after baseline.  

The dataset is split into training and testing sets in an 80-20 ratio using `train_test_split()` to allow for model evaluation on unseen data:
