# Car_Price_Prediction

# Car Price Prediction in Belarus by Nazarov Islom

This project aims to **predict car prices in Belarus** , **analyse car data** , **find the corralations**  using machine learning, based on key vehicle features like brand, year, engine specs, fuel type, transmission, mileage, and segment.

Using a **Decision Tree Regressor**, the model was trained on real-world car listings and achieved strong performance, with an R² score of **82.54%**, accurately capturing patterns in car pricing trends.

---

## 🚗 Project Highlights

- 📈 **Goal**: Predict car prices , finding corralations , analysing the data to get insights using historical and feature-based data
- 🧠 **Model Used**: DecisionTreeRegressor from `scikit-learn`
- 🔍 **EDA Insights**:
  - Post-2000 cars have notably higher prices.
  - Petrol and electric cars are generally more expensive.
  - Automatic transmission and all-wheel-drive cars have higher value.
  - Specialty and luxury European car segments dominate the top price range.
- 🏆 **Model Accuracy**: R² Score of **0.8254**

---

## 📊 Features Used

- `brand`
- `year`
- `engine_volume`
- `fuel_type`
- `transmission`
- `mileage`
- `drive_unit`
- `color`
- `segment`

---

## 🛠️ Tools & Libraries

- Python 3
- `pandas`, `numpy`, `matplotlib`, `seaborn` — for EDA & visualization
- `scikit-learn` — for model building & evaluation

---

## 📁 Files

- `code.ipynb`: Full notebook with data preprocessing, EDA, model training, and evaluation.
- `cars.csv`: Source data

---

## 📌 How to Run the Project

1. Clone the repository  
   ```bash
   git clone https://github.com/joebayden/Car_Price_Prediction.git
   cd Car_Price_Prediction
