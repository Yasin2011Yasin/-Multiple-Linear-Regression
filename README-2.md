# 🏠 House Price Prediction — Regression Portfolio Project

Predicting house prices based on physical and location-based features of apartments.

---

## 🗂️ Project Structure

```
regression-project/
│
├── data/
│   └── housing_data.csv      # Main dataset
│
├── notebooks/
│   └── exploration.ipynb     # EDA and prototyping
│
├── src/
│   ├── preprocess.py         # Data cleaning and feature engineering
│   ├── train.py              # Model training
│   ├── evaluate.py           # Metrics and evaluation
│   └── visualize.py          # Plotting results
│
├── outputs/
│   ├── models/               # Saved model files
│   └── plots/                # Generated charts
│
├── requirements.txt
└── README.md
```

---

## 📦 Dataset — `housing_data.csv`

The dataset contains **40 apartment samples** with the following features:

| Column | Description | Type |
|---|---|---|
| `area_m2` | Apartment area (square meters) | Numerical |
| `num_rooms` | Number of rooms | Numerical |
| `age_years` | Building age (years) | Numerical |
| `distance_to_center_km` | Distance to city center (km) | Numerical |
| `has_parking` | Has parking (0/1) | Binary |
| `has_elevator` | Has elevator (0/1) | Binary |
| `neighborhood_quality` | Neighborhood quality score (1–10) | Numerical |
| `price_million_toman` | **Price in million Toman — target variable** | Numerical |

---

## 🎯 Goal

Predict `price_million_toman` from 7 input features using multiple regression models.

---

## 🔧 Installation

```bash
git clone https://github.com/your-username/regression-project.git
cd regression-project
pip install -r requirements.txt
```

---

## 🚀 How to Run

```bash
# 1. Preprocess the data
python src/preprocess.py

# 2. Train the model
python src/train.py

# 3. Evaluate the model
python src/evaluate.py
```

---

## 🧠 Models Used

| Model | Library |
|---|---|
| Linear Regression | `scikit-learn` |
| Ridge / Lasso | `scikit-learn` |
| Random Forest Regressor | `scikit-learn` |
| XGBoost Regressor | `xgboost` |

---

## 📈 Evaluation Metrics

| Metric | Description |
|---|---|
| **MAE** | Mean Absolute Error (million Toman) |
| **RMSE** | Root Mean Squared Error |
| **R²** | Coefficient of Determination (closer to 1 is better) |

---

## 📊 Results

> *(Fill in after training)*

| Model | MAE | RMSE | R² |
|---|---|---|---|
| Linear Regression | — | — | — |
| Ridge | — | — | — |
| Random Forest | — | — | — |
| XGBoost | — | — | — |

---

## 📦 Requirements

```
pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn
jupyter
```

---

## 👤 Author

**[Your Name]**  
[GitHub](https://github.com/your-username) · [LinkedIn](https://linkedin.com/in/your-profile)

---

## 📄 License

MIT License
