📊 Economic Index Regression
📌 Overview

This project uses Linear Regression to predict the Index Price based on two key economic indicators:

Interest Rate

Unemployment Rate

It demonstrates a complete machine learning workflow including data analysis, train-test split, model training, evaluation, and visualization.

🗂️ Dataset

File: economic_index.csv
Columns:

year – Year of observation

month – Month number (1–12)

interest_rate – Interest rate in %

unemployment_rate – Unemployment rate in %

index_price – Target variable (economic index level)

⚙️ Workflow

Load dataset and explore structure.

Visualize correlations and trends.

Define features (interest_rate, unemployment_rate) and target (index_price).

Split into train (75%) and test (25%) sets.

Train a Linear Regression model.

Evaluate using MAE, RMSE, and R².

Plot Actual vs Predicted results and residuals.

✅ Results

On the test set, the model achieved:

R² Score: ~0.66

MAE: ~39.6

RMSE: ~44.6

This means the model explains about 66% of the variance in index prices using just two features.

🛠️ Installation
pip install -r requirements.txt

▶️ Usage

Run the notebook or Python script:

jupyter notebook Economic_Index_Regression.ipynb

python economic_index_model.py

📸 Sample Output Example regression line on scatterplot:
<img width="971" height="762" alt="image" src="https://github.com/user-attachments/assets/b0c3a14e-d0c0-4796-bf0c-598a46a7c752" />


📚 Tech Stack

Python

Pandas, NumPy

Scikit-learn

Matplotlib

🚀 Future Improvements

Add polynomial or regularized regression (Ridge/Lasso).

Include lag features for time-series forecasting.

Use walk-forward validation for robust evaluation.

✍️ Author: Abhishek Kumar
