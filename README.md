# 🏠 Sales Prediction Model

## Overview
This project focuses on building a regression-based machine learning model to predict house sales prices. It analyzes various property features like price, area, number of bedrooms, bathrooms, furnishing status, and more to estimate the value of residential properties.

## 📁 Dataset
The dataset includes the following key columns:
- `price`: Target variable representing the house price
- `area`: Size of the property
- `bedrooms`, `bathrooms`, `stories`: Basic features of the house
- `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`: Boolean categorical variables
- `parking`, `prefarea`, `furnishingstatus`: Additional categorical/ordinal features

## 🛠️ Tools & Libraries Used
- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

## 🧠 Model
- Data preprocessing: Missing value handling, encoding categorical features
- Feature scaling
- Regression algorithms: Linear Regression (can be extended to others like Random Forest, Gradient Boosting)
- Evaluation Metrics: R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE)

## 📊 Output
- Trained regression model
- Visualizations showing feature correlations and prediction results
- Performance metrics to evaluate model accuracy

## 🚀 How to Run
1. Clone the repository
2. Install required libraries using `pip install -r requirements.txt`
3. Run the notebook or Python script:  
   ```bash
   python sales_prediction.py
