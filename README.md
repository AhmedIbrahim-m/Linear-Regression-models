# 🏠 House Price Prediction using Regression

This project implements regression techniques to predict house prices based on various features from a housing dataset. It includes Exploratory Data Analysis (EDA), Simple Linear Regression, Multiple Linear Regression, and Polynomial Regression.

## 📁 Dataset
- **File**: `house_price_regression_dataset.csv`
- **Features**: `Square_Footage`, `Num_Bedrooms`, `Num_Bathrooms`, `Year_Built`, `Lot_Size`, `Garage_Size`
- **Target**: `House_Price`

## 📊 Exploratory Data Analysis
- **Scatter Plots**: Feature vs House_Price relationships.
- **Boxplot**: House price distribution and outliers.
- **Heatmap**: Correlation matrix to identify strong predictors.

## 📈 Regression Models
### ✅ Simple Linear Regression
- **Feature Used**: `Square_Footage`
- **Metrics**: R² Score, Mean Squared Error (MSE)

### ✅ Multiple Linear Regression
- **Features Used**: All six numerical predictors
- **Scaling**: Applied StandardScaler
- **Metrics**: R² Score, MSE, Root MSE (RMSE)

### ✅ Polynomial Regression
- **Degree**: 2, 3, 4
- **Pipeline**: PolynomialFeatures → StandardScaler → LinearRegression
- **Metrics**: R² Score, RMSE
- **Visualization**: Actual vs Predicted house prices for each polynomial degree

## 🛠️ Technologies Used
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## 🧪 How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
python house_price_regression.py
```

## 📌 Notes
- Ensure dataset path is correct in your script.
- Random seed fixed using `random_state=42` for reproducibility.

## 🧠 Author
- [Ahmed Ibrahim ]
- (Linkedin )-> https://www.linkedin.com/in/ahmed-ibrahim-2054b32a3/
