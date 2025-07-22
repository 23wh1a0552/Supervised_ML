# Ad Click Prediction - Logistic Regression 

This project applies **Logistic Regression** to predict whether a user will **click on an online advertisement** based on user behavior and demographic features.

---

##  Problem Statement
We are given a dataset containing information about internet users such as:
- Time spent on site
- Age
- Internet usage
- Geographic data

Our goal is to predict whether a user will **click on an ad (1)** or **not (0)**.

---

## Dataset Features
- `Daily Time Spent on Site`: Minutes user spends on site
- `Age`: Age of the user
- `Area Income`: Average income in user’s area
- `Daily Internet Usage`: Avg. daily internet usage in minutes
- `Ad Topic Line`, `City`, `Country`, `Timestamp`: Textual/context data
- `Male`: Gender (1 = Male, 0 = Female)
- `Clicked on Ad`: Target label (1 or 0)

---

## 🛠️ Libraries Used
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn` (`train_test_split`, `LogisticRegression`, `classification_report`)

---

##  Key Steps
1. Exploratory Data Analysis (EDA)
2. Data preprocessing
3. Splitting train/test
4. Fitting Logistic Regression
5. Evaluating model with classification metrics

---

## 📈 Outcome
A classification model that can **predict ad clicks** with decent accuracy and is explainable with logistic regression coefficients.

---

## 📂 File Info
- `ad_click_prediction.ipynb` – Jupyter Notebook with full code, EDA, model training, and evaluation.
