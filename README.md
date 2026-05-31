# 🚗 Car Price Prediction

A Machine Learning project that predicts the price of a car based on features like brand, manufacturing year, and mileage using Linear Regression.

---

## 📌 Overview

Buying or selling a car at the right price can be tricky. This project uses historical car data and a Linear Regression model to estimate the fair market price of a car based on its key attributes.

---

## ✨ Features

- Predicts car price based on:
  - 🏷️ Brand / Manufacturer
  - 📅 Manufacturing Year
  - 🛣️ Mileage / Kilometers Driven
- Data preprocessing and feature engineering
- Model training and evaluation
- Price prediction on new/unseen data

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)

---

## 📁 Project Structure

```
car-price-prediction/
│
├── data/
│   └── car_data.csv          # Dataset
│
├── notebooks/
│   └── car_price_prediction.ipynb  # Main notebook
│
├── model/
│   └── linear_model.pkl      # Saved trained model
│
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/sanikapatharkar6/car-price-prediction.git
cd car-price-prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
```bash
jupyter notebook notebooks/car_price_prediction.ipynb
```

---

## 📊 Model Performance

| Metric | Score |
|--------|-------|
| Algorithm | Linear Regression |
| R² Score | *(add your score here)* |
| MAE | *(add your score here)* |
| RMSE | *(add your score here)* |

---

## 📈 Sample Prediction

```python
# Example input
car = {
    "brand": "Maruti",
    "year": 2018,
    "kms_driven": 45000
}

# Predicted price
predicted_price = model.predict([car_features])
print(f"Estimated Price: ₹{predicted_price[0]:,.0f}")
```

---

## 🙋‍♀️ Author

**Sanika Patharakar**
- GitHub: [@sanikapatharkar6](https://github.com/sanikapatharkar6)
- LinkedIn: [sanika-patharkar](https://www.linkedin.com/in/sanika-patharkar-458345321?)

---

⭐ If you found this project helpful, please give it a star!
