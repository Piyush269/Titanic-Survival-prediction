# Titanic-Survival-prediction
This repository contains a comprehensive machine learning project focused on predicting passenger survival from the Titanic disaster using the classic Titanic dataset. The goal was to explore, preprocess, and model the data using various machine learning techniques and optimize them for the best accuracy.
## Project Highlights

### Binary Classification Problem
Predicting whether a passenger survived (`1`) or not (`0`) using the Titanic dataset.

---

### Two ML Models Implemented
- **Logistic Regression**  
  A simple and interpretable baseline model.

- **Random Forest Classifier**  
  An ensemble method that offers improved performance over linear models.

---

### Performance Improvements
- Applied **Bayesian Optimization** using the **Optuna** library to fine-tune hyperparameters.
- Significantly boosted model accuracy through systematic optimization and feature engineering.
- Compared performance before and after optimization to demonstrate improvements.

---

### Preprocessing Techniques
- Handled missing values in:
  - `age`
  - `embarked`
  - `fare`
- Feature engineering:
  - Created `family_size` feature
  - Extracted `title` from name
  - Used `OneHotEncoder` for categorical variables
- Normalized numerical features to improve model convergence.

---

### Model Evaluation
- Evaluated models using **cross-validation accuracy** and **test set performance**.
- Used **Optuna's contour plots** to visualize hyperparameter interactions.
- Compared **training vs test accuracy** to check for overfitting or underfitting.

---

### Tools & Libraries Used
- **Python**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Scikit-learn**
- **Optuna** (for Bayesian Optimization)
