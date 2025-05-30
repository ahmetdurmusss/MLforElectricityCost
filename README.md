# ⚡ Electricity Price Prediction

This project predicts electricity prices using various regression models and real-world energy production datasets. The goal is to build machine learning models to estimate SMP (System Marginal Price) based on features like wind production, temperature, and load.

## 📁 Project Structure

```
ElectricityPricePrediction/
├── ElectricityPricePrediction_CLEAN.ipynb   
├── data/
│   └── data.csv                                                        
└── requirements.txt                        
```

## 🚀 How to Run

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Open and run the Jupyter notebook:
```bash
jupyter notebook ElectricityPricePrediction_CLEAN.ipynb
```

## 📊 Models Used

- Linear Regression
- Support Vector Regression (SVR)
- XGBoost Regressor

## 📈 Evaluation Metrics

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
