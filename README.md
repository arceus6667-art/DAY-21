🏦 Banking Loan Approval Prediction System

A Machine Learning project that predicts whether a customer’s loan application will be approved or rejected using real-world inspired banking data and advanced modeling techniques.

🚀 Project Overview

Banks rely on data-driven decision systems to minimize risk while approving loans.

This project simulates a real-world banking decision system using a large-scale dataset and applies Machine Learning to predict loan approval outcomes based on customer and financial attributes.

🎯 Objective

To build a robust classification model that predicts:

LOAN_APPROVAL

1 → Approved

0 → Rejected

📊 Dataset Details

📁 Size: 100,000 rows

📌 Type: Synthetic but realistic

🔀 Features: Mixed (Numerical + Categorical)

Key Features:

Customer Info: age, job, marital, education

Financial Data: balance, default, housing_loan, personal_loan

Interaction Data: contact, duration, campaign

Previous Records: pdays, previous, poutcome

🔍 Exploratory Data Analysis (EDA)

Performed deep analysis using:

📈 Histograms (distribution analysis)

📊 Barplots (categorical insights)

🔥 Scatterplots (feature relationships)

🌡️ Heatmaps (correlation analysis)

🌐 3D Interactive Visualizations (advanced insights using Plotly)

⚙️ Machine Learning Pipeline

Data Preprocessing

Label Encoding for categorical variables

Train-Test Split (80-20)

Model Used: XGBoost Classifier

Hyperparameter Tuning: GridSearchCV

🧠 Model Performance

Optimized using hyperparameter tuning

Evaluated using:

Accuracy

ROC-AUC Score

Classification Report

🛠️ Tech Stack

Python 🐍

Pandas & NumPy

Matplotlib & Seaborn

Plotly (Interactive Visuals)

Scikit-learn

XGBoost

📁 Project Structure
├── data/
│   └── banking_loan_approval_dataset.csv
├── notebook/
│   └── eda_model.ipynb
├── src/
│   └── model.py
├── README.md
🚀 How to Run
pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost
python model.py
🔥 Key Highlights

Large dataset (100K rows)

Realistic feature relationships

Advanced EDA with interactive plots

Hyperparameter tuning for better performance

End-to-end ML workflow

📈 Future Improvements

Add SHAP for model explainability

Deploy using Flask / Streamlit

Try CatBoost & LightGBM

Feature Engineering for better accuracy

🤝 Connect With Me

If you like this project or want to collaborate, feel free to connect!

⭐ Support

If you found this useful, don’t forget to star ⭐ the repo — it really helps!
