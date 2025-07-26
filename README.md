# 📈 Airbnb Stock Price Prediction using Machine Learning

This project demonstrates how to predict Airbnb's stock closing prices using Machine Learning models like **Decision Tree Regressor** and **Random Forest Regressor**. We explore historical stock data, perform feature engineering, train models, and visualize actual vs. predicted prices.

---

## 🗂️ Project Structure
├── ABNB.csv # Dataset containing historical Airbnb stock data

├── stock_price_prediction.py # Python script for data processing, model training, and visualization

└── README.md # Project documentation

---

## 🧰 Tech Stack & Libraries Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

### 1. **Data Loading & Preprocessing**
- Load Airbnb historical stock prices from `ABNB.csv`.
- Convert `Date` column to datetime format and set it as index.
- Visualize the stock closing price history.

### 2. **Feature Engineering**
- Extract useful features like **year**, **month**, **day**, and **day of the week** from the date.

### 3. **Model Training**
- Split dataset into training and testing sets.
- Train two models:
  - **Decision Tree Regressor**
  - **Random Forest Regressor**

### 4. **Model Evaluation**
- Evaluate model performance using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R-squared Score (R²)

### 5. **Visualization**
- Plot actual vs. predicted closing stock prices.
- Compare model performance visually to assess prediction accuracy.

---

## 📈 Results (Example Metrics)
| Model                    | MAE     | MSE     | RMSE    | R² Score |
|--------------------------|---------|---------|---------|----------|
| Decision Tree Regressor   | *0.47450*  | *0.56476*  | *0.99932*  | *0.751506*  |
| Random Forest Regressor   | *0.293411*  | *0.2213*  | *0.99973*  | *0.47046*  |

> *(Fill in the metrics after running the code with your dataset.)*

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/airbnb-stock-price-prediction.git
   cd airbnb-stock-price-prediction

