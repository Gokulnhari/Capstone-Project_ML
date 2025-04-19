# Car Price Prediction

## Problem Description
A Chinese automobile company aims to enter the US market by setting up local manufacturing and competing with US and European automakers. To understand pricing dynamics, they have partnered with an automobile consulting firm to analyze factors affecting car prices in the American market.

## Business Goal
The goal is to build a predictive model that helps management understand the key variables influencing car prices. This model will assist in designing cars, optimizing business strategies, and setting competitive price levels.

## Dataset
The dataset consists of various car attributes and their prices, collected through market surveys in the US.

**Dataset Link**: https://github.com/Gokulnhari/Capstone-Project_ML/blob/main/CarPrice_Assignment.csv

## Features & Workflow

### Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling

### Exploratory Data Analysis (EDA)
- Identified key factors affecting car prices through visualizations and statistical summaries

### Model Training & Evaluation
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regression**
- **Support Vector Regression**
- **Gradient Boosting Regressor** *(Best Performing Model)*

### Feature Importance
- Analyzed the influence of features on the final prediction using the best-performing model.

### Hyperparameter Tuning
- Used `RandomizedSearchCV` to fine-tune the Gradient Boosting model for better performance.

### Prediction on Test Data
- Evaluated using:
  - **Mean Absolute Error (MAE)**: 2089.8
  - **Mean Squared Error (MSE)**: 9591642.07
  - **Root Mean Squared Error (RMSE)**: 3097.03
  - **R² Score**: 0.889

## Results
**Best Model**: Gradient Boosting Regressor

## Installation & Usage
```bash
git clone https://github.com/yourusername/car-price-prediction.git
cd car-price-prediction
pip install -r requirements.txt
```

Run the Jupyter Notebook to train the model and test predictions.

## Technologies Used
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Machine Learning Models:
  - Random Forest
  - SVR
  - Linear Regression
  - Decision Tree Regression
  - Gradient Boosting Regression

## Future Improvements
- Include deep learning models for better accuracy.
- Deploy the model as a web application for real-time predictions.
- Integrate more features like car age, brand reputation, and mileage.

## Author
**Gokul N Hari**

