# 🚗 Car Price Prediction Using Machine Learning

This project focuses on predicting the prices of used cars based on various features. The data is scraped from the [Quikr](https://www.quikr.com) website and processed before applying different machine learning models to find the most accurate one. The **Random Forest Regressor** model gave the best results with an accuracy of **88%**.

## 📌 Project Overview

- Scraped used car listings from Quikr.
- Cleaned and preprocessed the data (handled missing values, converted data types, feature engineering).
- Applied multiple regression models:
  - Linear Regression
  - XGBoost Regressor
  - Random Forest Regressor
  - Decision Tree Regressor
- Compared models based on performance metrics.
- Random Forest Regressor achieved the best accuracy (88%).

---

## 🛠️ Tech Stack

- **Python** (Pandas, NumPy, Scikit-learn, XGBoost)
- **Jupyter Notebook / VS Code**
- **BeautifulSoup / Requests** (for web scraping)
- **Matplotlib / Seaborn** (for visualization)

---

## 📊 Dataset

The dataset was self-collected using web scraping from Quikr.com and includes the following features:

- Car Name
- company name
- Year of Manufacture
- Kilometers Driven
- Fuel Type
- Price

---

## 📈 Model Evaluation

| Model                  | Accuracy Score |
|------------------------|----------------|
| Linear Regression      | ~84%           |
| Decision Tree Regressor| ~86%           |
| XGBoost Regressor      | ~86%           |
| **Random Forest Regressor** | **88%**     |

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git
   cd car-price-prediction
