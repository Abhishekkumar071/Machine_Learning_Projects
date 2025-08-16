# 📊 Project 1: Height-to-Weight Prediction  

## 📌 Overview  
This project predicts **human height from weight** using a **Linear Regression model**.  
It demonstrates the end-to-end ML workflow: data preprocessing, visualization, training, evaluation, and prediction.  

---

## 📂 Dataset  
- File: `height-weight.csv`  
- Columns:  
  - **Height** → Person’s height in cm  
  - **Weight** → Person’s weight in kg  

---

## 🚀 Steps in the Notebook  
1. Import required libraries  
2. Load dataset  
3. Data exploration & visualization (scatterplots, correlation)  
4. Train-test split  
5. Linear Regression model training  
6. Model evaluation (MAE, RMSE, R² score)  
7. Predictions on new data  

---

## 📈 Results  
- **R² Score:** 0.777  
- **MAE:** 9.82  
- **RMSE:** 10.48  

The model explains about **77.7% of the variance** in height based on weight.  

---

## 🛠️ Installation  
Install dependencies:
pip install -r requirements.txt

▶️ Usage
Open the Jupyter Notebook:

bash
Copy code
jupyter notebook heightToWeight_Prediction.ipynb

📸 Sample Output
Example regression line on scatterplot:
<img width="901" height="664" alt="image" src="https://github.com/user-attachments/assets/145ff971-88bd-4610-bbd9-b18c0ef8bcbe" />

📚 Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn

📌 Future Improvements
Try Polynomial Regression for non-linear patterns

Compare with other ML models (Decision Tree, Random Forest)

Deploy using Streamlit for interactive web app

✍️ Author: Abhishek Kumar
