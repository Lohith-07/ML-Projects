# 🛍️ Customer Purchase Prediction

A beginner Machine Learning project to predict whether a customer will purchase a product based on their **Gender**, **Age**, and **Estimated Salary** using Logistic Regression.

---

## 📌 Problem Statement

Businesses aim to identify which customers are likely to make a purchase. This binary classification task uses customer demographic data to predict purchasing behavior, allowing companies to target the right users more efficiently.

---

## 🧾 Dataset Description

- **File Used**: `Shop.csv`
- **Source**: Imported from local Google Drive path
- **Features**:
  - `Gender` - Categorical (Male/Female)
  - `Age` - Integer
  - `EstimatedSalary` - Numerical
  - `Purchased` - Target variable (0 = No, 1 = Yes)

> `User ID` was removed since it’s irrelevant to prediction.

---

## 📊 Exploratory Data Analysis (EDA)

- **Age Distribution** using histogram with KDE
- **Gender Proportion** via pie chart
- **Salary Distribution** visualized using boxplot
- **Purchase vs Age** with KDE plots
- **Purchase vs Salary** with KDE plots
- **Correlation Matrix** to understand numerical relationships

---

## 🧼 Data Preprocessing

- Categorical Encoding: `Gender` column label encoded
- Standard Scaling: Applied on `Age` and `Salary`
- Data Split: 80% training, 20% testing

---

## ⚙️ Model Used

### ✔️ Naive Bayes Classification
- Trained on scaled data
- Evaluated using:
  - Confusion Matrix
  - Accuracy Score
  - Classification Report (Precision, Recall, F1)

---

## 📈 Model Evaluation

- **Accuracy**: ~94%
- Strong balance between **precision** and **recall**
- Confusion matrix confirms low false positives/negatives

---

