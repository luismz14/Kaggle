# Car Price Prediction Challenge

A machine learning project to predict car prices based on various features. This project is based on the Kaggle **Car Price Prediction Challenge** dataset from [Kaggle](https://www.kaggle.com/datasets/deepcontractor/car-price-prediction-challenge).

This project was developed for the Computational Learning subject in the Informatics Engineering course at [UAB](https://www.uab.es).

## Table of Contents

- [About the project](#about-the-project)
- [Dataset](#dataset)
- [Installation](#installation)
- [Model and Results](#model-and-results)
- [Acknowledgements](#acknowledgements)

---

## 🛠 About the project

This project explores the relationship between car features and their prices using machine learning models. It includes data preprocessing, exploratory data analysis (EDA), and model training.

The main objectives are:
- Understand key factors influencing car prices.
- Build a model thats predict car prices with high accuracy.

---

## 📂 Dataset

The dataset is from the [Kaggle Car Price Prediction Challenge](https://www.kaggle.com/datasets/deepcontractor/car-price-prediction-challenge). It includes:
- **Features**: Car brand, model, year of manufacture, mileage, engine capacity, fuel type, etc.
- **Target**: Price of the car.

If you want to use the dataset, download it from Kaggle and place it in the directory: 
    data
    └──car_price_prediction.csv

---

## 💻 Installation

1. Clone the repository:
```bash
git clone https://github.com/luismz14/Kaggle
```
2. Navigate to the project directory:
```bash
cd Kaggle
``` 
3. Install the required packages:
```bash
pip install -r requirements.txt
```
---

## 📊 Model and Results

The best-performing model was a Random Forest Regressor with n_estimators=96 and max_depth=17.

| Metric | Train Set | Test Set |
|--------|-----------|----------|
| MAE    | 0.057571  | 0.083994 |
| R²     | 0.854309  | 0.711058 |

## 🙌 Acknowledgements

* [Kaggle](https://www.kaggle.com)
* [Random Forest Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Scikit-learn](https://scikit-learn.org/stable/)
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)