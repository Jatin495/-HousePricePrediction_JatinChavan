# -HousePricePrediction_JatinChavan
House Price Prediction using Machine Learning with Linear Regression and Random Forest Regressor. Includes data preprocessing, feature engineering, visualization, model evaluation, and price prediction analysis.
# House Price Prediction 🏠

A Machine Learning project that predicts house prices based on property features such as area, number of bedrooms, bathrooms, parking availability, furnishing status, and other amenities.

## 📌 Project Overview

The goal of this project is to build regression models capable of estimating house prices accurately. The project includes data preprocessing, exploratory data analysis, visualization, model training, evaluation, and comparison of different machine learning algorithms.

## 🎯 Objectives

* Load and explore the housing dataset.
* Clean and preprocess the data.
* Convert categorical features into numerical format.
* Train and evaluate regression models.
* Compare Linear Regression and Random Forest Regressor.
* Visualize important patterns and relationships in the data.
* Identify key factors influencing house prices.

## 📂 Dataset

* **Dataset:** Housing Prices Dataset
* **Source:** Kaggle
* **File:** `Housing.csv`

### Features

* Area
* Bedrooms
* Bathrooms
* Stories
* Parking
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Preferred Area
* Furnishing Status

### Target Variable

* Price

## 🛠 Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## 📊 Data Preprocessing

* Checked for missing values
* Removed duplicate records
* Converted categorical variables using One-Hot Encoding
* Prepared data for machine learning models

## 🤖 Machine Learning Models

### 1. Linear Regression

Used as a baseline regression model for house price prediction.

### 2. Random Forest Regressor

Used to improve prediction accuracy and capture non-linear relationships between features.

## 📈 Visualizations

* House Price Distribution Histogram
* Correlation Heatmap
* Actual vs Predicted Price Scatter Plot

## 📏 Evaluation Metrics

The models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

## 🔍 Key Findings

* Area is one of the strongest factors affecting house prices.
* Houses with better amenities generally have higher prices.
* Preferred location significantly impacts property value.
* Random Forest Regressor performed better than Linear Regression.

## 📁 Project Structure

```text
HousePricePrediction/
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
│
└── charts/
    ├── house_price_distribution.png
    ├── correlation_heatmap.png
    └── actual_vs_predicted.png
```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run `analysis.ipynb`.

## 📌 Conclusion

This project demonstrates how machine learning can be applied to predict house prices effectively. By comparing multiple regression models and analyzing important features, valuable insights can be generated for real estate decision-making.

## 👨‍💻 Author

**Jatin Rajesh Chavan**

