# 🧪 Diabetes Prediction with Logistic Regression

This machine learning project uses a logistic regression model to predict the likelihood of diabetes in patients based on diagnostic measurements. We use a dataset of information on 768 diabetes patients, including information such as:

- Pregnancies
- Glucose levels
- Blood pressure
- Skin thickness
- Insulin
- Body mass index (BMI)
- Diabetes pedigree function (considers history of diabetes in a patient's relatives)
- Age
Using this information, we are able to predict whether a patient is positive (1) or negative (0) for diabetes.

This project contains three implementations:

1. Using scikit-learn's built-in `LogisticRegression()` model
2. Implementing logistic regression from scratch, using *stochastic* gradient descent
3. Using PyTorch to create and train a logistic regression classifier

This project was originally written on Google Colab, hence the use of the `drive.mount()` function. It can be easily adjusted to run locally on your machine, however.

## 🧠 Project Summary

- **Algorithm**: Logistic Regression
- **Dataset**: `diabetes2.csv` (similar to the Pima Indians Diabetes dataset)
- **Libraries Used**: pandas, matplotlib, scikit-learn, pytorch
- **Goal**: Binary classification (e.g., diabetes vs. no diabetes)

## 📂 Files

- `LogisticRegression.ipynb` – Notebook containing model development and evaluation
- `diabetes2.csv` – Dataset with patient medical data

## 🔧 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/logistic-regression-diabetes.git
   cd logistic-regression-diabetes