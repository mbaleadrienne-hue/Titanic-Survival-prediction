# Titanic Survival Prediction

Predicting passenger survival on the Titanic using Machine Learning.

**Link to dataset:** Kaggle Titanic Dataset (891 passengers)

### Process

**1. Data Cleaning:**
- Dropped `Cabin` column (77% missing values)
- Filled `Age` missing values with median
- Filled `Embarked` missing values with most frequent value

**2. Data Preprocessing:**
- Encoded categorical variables `Sex` and `Embarked` using OneHotEncoder
- Train/Test split: 80% / 20%

**3. Modeling & Results:**
- Logistic Regression: 78% accuracy
- Random Forest: 75.4% accuracy

### Tech Stack
Python, Pandas, Scikit-Learn

Author: Adrienne Mbale
