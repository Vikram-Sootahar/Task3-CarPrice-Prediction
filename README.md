# UK Car Price Prediction — Machine Learning

## Task 3 — Car Price Prediction with Machine Learning

### Overview
This project builds a complete Machine Learning pipeline to predict
used car prices in the UK market. The project covers data generation,
preprocessing, feature engineering, model training, evaluation, and
real-world price prediction using three regression algorithms.
The best model achieved 92.03% accuracy using Gradient Boosting.

---

## Dataset

- Source: Self-generated based on UK Used Cars Market Data
- Total Records: 300
- Total Features: 9
- Year Range: 2010 - 2023
- Price Range: GBP 2,000 - 39,200
- Brands Covered: 10 major UK car brands

---

## Dataset Features

| Feature | Description | Type |
|---------|-------------|------|
| Brand | Car manufacturer | Categorical |
| Model | Car model name | Categorical |
| Year | Year of manufacture | Numerical |
| Fuel_Type | Petrol, Diesel, Hybrid, Electric | Categorical |
| Transmission | Manual or Automatic | Categorical |
| Engine_Size | Engine size in litres | Numerical |
| Mileage | Total kilometres driven | Numerical |
| Owners | Number of previous owners | Numerical |
| Price_GBP | Selling price in GBP (Target) | Numerical |

---

## Project Structure

| File | Description |
|------|-------------|
| car_price_prediction.ipynb | Dataset creation, data cleaning, 12 visualization charts |
| ml_model.ipynb | Feature engineering, model training, evaluation, predictions |
| feature_engineering.ipynb | Label encoding, correlation analysis, feature importance |

---

## Machine Learning Models

| Model | MAE | RMSE | R2 Score |
|-------|-----|------|---------|
| Linear Regression | £5,376 | £6,438 | 43.72% |
| Random Forest | £2,908 | £3,573 | 82.66% |
| Gradient Boosting | £1,983 | £2,422 | 92.03% |

**Best Model: Gradient Boosting Regressor — 92.03% Accuracy**

---

## Sample Predictions

| Brand | Year | Fuel Type | Transmission | Predicted Price |
|-------|------|-----------|--------------|----------------|
| BMW | 2020 | Petrol | Automatic | £30,867 |
| Ford | 2018 | Diesel | Manual | £10,575 |
| Mercedes | 2022 | Hybrid | Automatic | £38,410 |
| Toyota | 2016 | Petrol | Manual | £11,865 |
| Nissan | 2021 | Electric | Automatic | £23,994 |

---

## Features

- UK used car dataset with 300 records and 10 brands
- Complete data cleaning and preprocessing pipeline
- Feature engineering — Age feature extraction and Label Encoding
- 12 interactive visualization charts
- Three regression models trained and compared
- Model evaluation using MAE, RMSE, and R2 Score
- Real-world car price predictor with sample predictions
- Correlation heatmap and feature importance analysis

---

## Technologies Used

| Library | Version | Purpose |
|---------|---------|---------|
| Python | 3.x | Core programming language |
| Pandas | 2.3.3 | Data manipulation and analysis |
| NumPy | 2.3.5 | Numerical computations |
| Matplotlib | 3.10.6 | Data visualization |
| Seaborn | 0.13.2 | Statistical visualization |
| Scikit-learn | 1.7.2 | Machine Learning models |

---

## How to Run

1. Install required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn
2. Open Jupyter Notebook
3. Run car_price_prediction.ipynb first — creates dataset and visualizations
4. Run feature_engineering.ipynb — label encoding and correlation analysis
5. Run ml_model.ipynb — trains models and predicts car prices

---

## Key Findings

- Gradient Boosting achieved highest accuracy at 92.03%
- Mercedes and BMW have highest average prices above GBP 26,000
- Electric cars are priced GBP 5,000 higher than Petrol on average
- Mileage and Age are strongest negative predictors of price
- Automatic transmission adds approximately GBP 1,500 to car value
- Cars with 1 owner are valued GBP 3,000 higher than 3 owner cars
- Engine size has strong positive correlation with price

---

## Model Workflow

Data Collection → Data Cleaning → Feature Engineering → Train Test Split → Model Training → Model Evaluation → Best Model Selection → Price Prediction

---

## Author

- Name: Vikram Sootahar
- Subject: Data Science and Python Analytics
- Project: Task 3 — Car Price Prediction with Machine Learning
- Institution: CodeAlpha
