🚗 Car Price Prediction using Machine Learning
📌 Project Overview

This project aims to predict the price of cars based on their specifications such as engine size, horsepower, torque, acceleration, and year of manufacture.
We apply Multiple Linear Regression (MLR) and Random Forest Regression to evaluate which model best fits the dataset.

The dataset contains 1,000 rows and 8 features, including both categorical (Car Make, Car Model) and numerical variables (Engine Size, Horsepower, Torque, etc.).

🔑 Features Used (Predictors)

Year

Engine Size (L)

Horsepower

Torque (lb-ft)

0-60 MPH Time (seconds)

Car Make (optional for future extensions)

Target Variable:

Price (in USD)

📊 Exploratory Data Analysis (EDA)

Distribution plots of numerical features.

Correlation heatmap to identify strong predictors of price.

Scatter plots of features vs. car price.

Boxplots to check for outliers.

🧠 Models Implemented

Multiple Linear Regression (MLR)

Achieved R² ≈ 0.95 on test set.

Cross-validation Mean R² ≈ 0.94, Std Dev ≈ 0.03 (stable & reliable).

Random Forest Regression

Achieved R² ≈ 0.91 on cross-validation.

Slightly lower performance compared to MLR.

✅ Best Model: Multiple Linear Regression (simpler, more interpretable, and higher accuracy).

📈 Results & Insights

Car price strongly correlates with Engine Size, Horsepower, and Torque.

Year of manufacture also impacts price, but less than performance features.

Random Forest underperformed compared to Linear Regression, likely due to the dataset being small and linear in nature.

🛠️ Tech Stack

Python

Pandas, NumPy (data manipulation)

Matplotlib, Seaborn (visualization)

Scikit-Learn (ML models & evaluation)

🚀 How to Run

Clone the repo:

git clone https://github.com/yourusername/car-price-prediction.git
cd car-price-prediction


Install dependencies:

pip install -r requirements.txt


Open Jupyter Notebook:

jupyter notebook CarPricePrediction.ipynb

📌 Future Improvements

Add more regression models (Lasso, Ridge, Gradient Boosting).

Perform hyperparameter tuning for Random Forest.

Include categorical encoding for Car Make/Model.

Deploy using Streamlit / Flask for interactive predictions.

📜 Conclusion

MLR is the best model for this dataset (R² ≈ 0.95).

Car performance metrics (engine size, horsepower, torque) are the strongest predictors of price.

The project demonstrates the end-to-end ML pipeline: Data Cleaning → EDA → Modeling → Evaluation.

⭐ If you like this project, don’t forget to star this repo!